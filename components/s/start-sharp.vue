<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1edl9bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:start-sharp" /></template>
<style>
.e1edl9bpw {
  fill: currentColor;
  d: path("M2 18V6h2v12zm14 0l-1.425-1.4l3.6-3.6H6v-2h12.175L14.6 7.4L16 6l6 6z");
}

</style>
