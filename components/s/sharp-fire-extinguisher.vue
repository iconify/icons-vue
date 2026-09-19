<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0klxqr0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fire-extinguisher" /></template>
<style>
.w0klxqr0z {
  fill: currentColor;
  d: path("M7 19h10v3H7zm0-1h10v-5H7zM17 3v6l-3.15-.66c-.01 0-.01.01-.02.02c1.55.62 2.72 1.98 3.07 3.64H7.1c.34-1.66 1.52-3.02 3.07-3.64c-.33-.26-.6-.58-.8-.95L5 6.5v-1l4.37-.91C9.87 3.65 10.86 3 12 3c.7 0 1.34.25 1.85.66zm-4 3c-.03-.59-.45-1-1-1s-1 .45-1 1s.45 1 1 1s1-.45 1-1");
}

</style>
