<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eest86b4b"/><path class="wd0ngcdib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-bold-duotone" /></template>
<style>
.eest86b4b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 12C22 10.9648 21.4695 9.92953 20.4086 9.35258L7.59661 2.38548C5.53435 1.26402 3 2.72368 3 5.0329L3 12H22Z");
}

.wd0ngcdib {
  fill: currentColor;
  d: path("M7.59662 21.6145L20.4086 14.6474C21.4695 14.0705 22 13.0352 22 12H3L3 18.9671C3 21.2763 5.53435 22.736 7.59662 21.6145Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
