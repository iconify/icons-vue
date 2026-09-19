<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw5vu58kl"/><path class="qukdhgbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-not-equal" /></template>
<style>
.qukdhgbip {
  fill: currentColor;
  d: path("m14.08 4.605l1.84.79l-6 14l-1.84-.79z");
}

.uw5vu58kl {
  fill: currentColor;
  d: path("M19 9.998H5v-2h14zm0 6H5v-2h14z");
}

</style>
