<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exwmfbbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pentagon-rounded" /></template>
<style>
.exwmfbbyo {
  fill: currentColor;
  d: path("M7.527 20.5q-.535 0-.954-.298q-.42-.298-.58-.808L2.974 10.33q-.161-.516 0-1.025q.162-.51.616-.808l7.49-5.235q.429-.292.919-.292t.92.292l7.49 5.235q.454.298.615.808q.162.51 0 1.025l-3.017 9.065q-.162.51-.581.808q-.42.298-.954.298z");
}

</style>
