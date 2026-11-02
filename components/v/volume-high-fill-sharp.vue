<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3smn57_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-fill-sharp" /></template>
<style>
.z3smn57_c {
  fill: currentColor;
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4m8.749 4.025A12.4 12.4 0 0 1 21.402 12a12.4 12.4 0 0 1-.653 3.975a12.3 12.3 0 0 1-1.96 3.639a1 1 0 1 1-1.578-1.228a10.3 10.3 0 0 0 1.643-3.052c.364-1.074.549-2.2.548-3.334a10.4 10.4 0 0 0-.548-3.334a10.3 10.3 0 0 0-1.643-3.052a1 1 0 1 1 1.578-1.228a12.3 12.3 0 0 1 1.96 3.639m-3.883 1.619c.23.764.345 1.558.345 2.356s-.115 1.592-.345 2.356a8.2 8.2 0 0 1-1.034 2.199a1 1 0 0 1-1.664-1.11a6.21 6.21 0 0 0 0-6.89a1 1 0 0 1 .277-1.387a1 1 0 0 1 1.387.277a8.2 8.2 0 0 1 1.034 2.199");
}

</style>
