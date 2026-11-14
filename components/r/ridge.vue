<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u425zobcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ridge" /></template>
<style>
.u425zobcu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.004 7.004q-.357.317-.585.831L11.83 11.41q-.167.375-.575.422q-.409.046-.655-.282l-.228-.304q-.699-.931-1.862-.899T6.7 11.348l-3.269 4.904q-.748 1.121-.112 2.31q.636 1.188 1.984 1.188h13.922q1.212 0 1.879-1.011q.667-1.012.189-2.125l-3.749-8.75q-.524-1.225-1.779-1.351l-1.194 3.412l1.83 3.203q.043.075.068.157q.024.083.03.168t-.009.171t-.048.164l-1.25 3q-.057.138-.163.243q-.105.106-.243.163q-.138.056-.288.056t-.286-.058q-.069-.028-.13-.069t-.113-.094q-.053-.052-.093-.114q-.041-.061-.07-.129q-.028-.069-.042-.141q-.014-.073-.014-.147q0-.073.015-.146q.014-.072.043-.14l1.108-2.66l-1.817-3.18q-.081-.141-.096-.304q-.015-.162.039-.316z");
}

</style>
