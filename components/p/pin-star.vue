<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp2uk16af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-star" /></template>
<style>
.qp2uk16af {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 10q0 5.488 8.262 12.569q.05.044.108.078q.057.033.12.056q.062.024.128.035q.065.012.132.012t.132-.012q.066-.011.128-.035q.063-.023.12-.056q.058-.034.108-.078Q20.75 15.488 20.75 10q0-3.624-2.563-6.187T12 1.25T5.813 3.813T3.25 10m10.075-3.644l.283.735q.171.445.647.479l.871.062q.967.069 1.282.986q.314.917-.407 1.565l-.592.533q-.329.296-.229.726l.176.765q.217.941-.561 1.515q-.779.573-1.614.086l-.803-.469q-.378-.221-.756 0l-.803.469q-.835.487-1.614-.086q-.778-.574-.561-1.516l.176-.763q.1-.431-.229-.727l-.593-.534q-.72-.647-.406-1.564q.315-.917 1.282-.986l.872-.062q.475-.034.646-.479l.283-.735q.351-.91 1.325-.91t1.325.909z");
}

</style>
