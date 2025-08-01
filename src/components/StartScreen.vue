<template>
  <div class="flex h-screen items-center justify-center bg-gray-100 dark:bg-gray-900">
    <button @click="onStart" class="px-6 py-4 text-xl font-semibold text-red-500 bg-green-500 rounded-lg hover:bg-green-600 focus:outline-none focus:ring-2 focus:ring-green-400">
      시작하기
    </button>
  </div>
</template>
<script setup>
const onStart = () => {
  console.log('Start clicked')
}
</script>
