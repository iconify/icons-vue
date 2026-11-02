<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhwrxb_7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-fill" /></template>
<style>
.jhwrxb_7u {
  fill: currentColor;
  d: path("M12 6v12c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C6.98 17.395 6.468 17 6 17H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C11.428 4.072 12 5.102 12 6m8.749 2.025A12.4 12.4 0 0 1 21.402 12a12.4 12.4 0 0 1-.653 3.975a12.3 12.3 0 0 1-1.96 3.639a1 1 0 1 1-1.578-1.228a10.3 10.3 0 0 0 1.643-3.052c.364-1.074.549-2.2.548-3.334a10.4 10.4 0 0 0-.548-3.334a10.3 10.3 0 0 0-1.643-3.052a1 1 0 1 1 1.578-1.228a12.3 12.3 0 0 1 1.96 3.639m-3.883 1.619c.23.764.345 1.558.345 2.356s-.115 1.592-.345 2.356a8.2 8.2 0 0 1-1.034 2.199a1 1 0 0 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1 1 0 0 1 .277-1.387a1 1 0 0 1 1.387.277a8.2 8.2 0 0 1 1.034 2.199");
}

</style>
