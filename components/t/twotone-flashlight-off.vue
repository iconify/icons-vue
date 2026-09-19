<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxwt4tbpw"/><path class="ni1ltcqyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-flashlight-off" /></template>
<style>
.mxwt4tbpw {
  fill: currentColor;
  d: path("M16 7H9.83L14 11.17v-.77l2-3.01zm-6 5.83V20h4v-3.17zM16 5V4H6.83l1 1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ni1ltcqyw {
  fill: currentColor;
  d: path("M2.81 2.81L1.39 4.22L8 10.83V22h8v-3.17l3.78 3.78l1.41-1.41zM14 20h-4v-7.17l4 4zm2-16v1H7.83l2 2H16v.39l-2 3.01v.77l2 2V11l2-3V2H6v1.17l.83.83z");
}

</style>
