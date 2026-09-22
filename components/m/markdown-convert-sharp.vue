<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcyjh8mul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:markdown-convert-sharp" /></template>
<style>
.jcyjh8mul {
  fill: currentColor;
  d: path("M2 20V4h20v4.95Q21.05 8 19.887 7.5T17.376 7h-2v4.75H14V20zm20 0h-6v-6h2v2.425q.925-.2 1.525-.95t.6-1.725q0-1.15-.812-1.95t-1.938-.8V9q1.975 0 3.363 1.388t1.387 3.362q0 1.425-.737 2.55T19.45 18H22zM5.5 15H7v-4.5h1v3h1.5v-3h1V15H12V9H5.5z");
}

</style>
