<script>
const route = useRoute();

console.log(route.params.id);
</script>

<template>
    event ID: {{ $route.params.id }}
</template>