<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8y8d7bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sales-tax-exempt" /></template>
<style>
.q8y8d7bjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.435 15.651l-2.5-2.955q-.075-.088-.141-.182q-.067-.094-.124-.194q-.058-.1-.108-.204q-.049-.105-.088-.213q-.04-.108-.07-.219q-.03-.112-.05-.225q-.02-.114-.03-.229t-.01-.23t.01-.23t.03-.229q.02-.113.05-.225q.03-.111.07-.219q.039-.108.088-.213q.05-.104.108-.204t.124-.194t.141-.182l3.279-3.875q.185-.218.412-.392q.228-.173.487-.293q.26-.121.539-.182q.279-.062.565-.062h8.316M21.5 8.465v6.41q0 .129-.013.257q-.012.129-.037.255q-.026.127-.063.25t-.087.243q-.049.119-.11.232t-.132.221t-.154.207q-.082.1-.173.191t-.191.173q-.099.082-.207.154q-.107.071-.221.132q-.113.061-.232.11q-.12.05-.243.087t-.25.063q-.126.025-.255.037q-.128.013-.257.013h-6.472M7.75 11h.01M12 8.5h.01m5.99 5h.01m-11.51 6l14-14");
}

</style>
