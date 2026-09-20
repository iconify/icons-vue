<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpsblwsvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vacuum-sharp" /></template>
<style>
.zpsblwsvn {
  fill: currentColor;
  d: path("M2.23 20.772q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728m2.828-.713Q5.5 19.617 5.5 19t-.441-1.059Q4.617 17.5 4 17.5t-1.059.441Q2.5 18.383 2.5 19t.441 1.059Q3.383 20.5 4 20.5t1.059-.441M7.75 21.5q.366-.554.558-1.196T8.5 19q0-1.868-1.316-3.184T4 14.5q-.385 0-.753.071t-.747.175V9.5h3V5.6q0-1.716 1.192-2.908T9.599 1.5q1.247 0 2.272.676t1.498 1.816L20.348 20.5H22.5v1h-6v-1h2.77L12.466 4.408q-.377-.86-1.153-1.384T9.6 2.5q-1.282 0-2.19.91q-.91.908-.91 2.19v3.9h1.73q1.459 0 2.48 1.021T11.73 13v8.5z");
}

</style>
