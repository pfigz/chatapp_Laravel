<script>
export default {
    props: ['message']
}
</script>

<template>
    {{ message.user.name }}: {{ message.message }}
</template>

