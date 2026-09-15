<script setup lang="ts">
defineProps<{
    message?: string;
}>();
</script>

<template>
    <div v-show="message">
        <p class="text-body-s text-app-primary dark:text-app-primary">
            {{ message }}
        </p>
    </div>
</template>
