<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5jhbbbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-charge-sharp" /></template>
<style>
.z5jhbbbbt {
  fill: currentColor;
  d: path("m11.5 17l3-6h-2V7l-3 6h2zM5 23V1h14v5.1h1v4.8h-1V23z");
}

</style>
