<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzdt1kbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rocket-sharp" /></template>
<style>
.wzdt1kbsv {
  fill: currentColor;
  d: path("M5.52 20.596V15.46q0-.404.189-.768q.189-.363.537-.58l1.196-.783q.175 1.754.454 3.036t.906 2.91zm4.051-1.788q-.605-1.535-.934-3.144t-.33-3.277q0-2.645.902-4.859q.9-2.214 2.791-3.928q1.89 1.714 2.791 3.928t.901 4.859q0 1.661-.329 3.268q-.328 1.607-.934 3.153zm3.495-6.742q.434-.433.434-1.066t-.434-1.066T12 9.5t-1.066.434Q10.5 10.367 10.5 11t.434 1.066T12 12.5t1.066-.434m5.396 8.53l-3.283-1.302q.627-1.627.906-2.919t.454-3.046l1.196.802q.348.217.537.58q.19.364.19.768z");
}

</style>
