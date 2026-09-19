<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q_06f8bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:small-orange-diamond" /></template>
<style>
.q_06f8bjf {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M32.725 56.013L8.407 32.077l24.32-23.941l24.315 23.941z");
}

</style>
