<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwdaz89vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-fill" /></template>
<style>
.mwdaz89vd {
  fill: currentColor;
  d: path("m5.852 5.397l7 4.5a2.5 2.5 0 0 1 0 4.206l-7 4.5A2.5 2.5 0 0 1 2 16.5v-9a2.498 2.498 0 0 1 3.852-2.103M16 18V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0m4 0V6a1 1 0 0 1 2 0v12a1 1 0 0 1-2 0");
}

</style>
