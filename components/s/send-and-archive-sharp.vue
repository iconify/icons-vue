<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="octa1qeuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:send-and-archive-sharp" /></template>
<style>
.octa1qeuk {
  fill: currentColor;
  d: path("M3 20v-6l8-2l-8-2V4l14.3 6H17q-2.925 0-4.962 2.063T10 17.05zm10.463.538Q12 19.075 12 17t1.463-3.537T17 12t3.538 1.463T22 17t-1.463 3.538T17 22t-3.537-1.463M17 20l3-3l-.7-.7l-1.8 1.8V14h-1v4.1l-1.8-1.8l-.7.7z");
}

</style>
