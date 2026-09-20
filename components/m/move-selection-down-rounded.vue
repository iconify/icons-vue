<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq70fbc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-down-rounded" /></template>
<style>
.rq70fbc2v {
  fill: currentColor;
  d: path("M8.577 21q-.671 0-1.143-.472q-.473-.472-.473-1.144V12.54q0-.672.473-1.144q.472-.472 1.143-.472h6.846q.671 0 1.143.472q.473.472.473 1.144v6.846q0 .67-.473 1.143q-.472.472-1.143.472zM15.99 8.01q-.182-.181-.182-.433t.182-.434t.433-.182t.434.182t.181.434t-.181.433t-.434.182t-.433-.182m0-3.961q-.182-.182-.182-.434t.181-.433t.434-.182t.434.182t.181.433t-.181.434t-.434.182t-.433-.182m-4.424 0q-.182-.182-.182-.434t.182-.433T12 3t.434.182t.182.434t-.182.433t-.434.182t-.434-.182m-4.423 0q-.181-.182-.181-.434t.181-.433T7.577 3t.434.182t.181.433t-.182.434t-.433.182t-.434-.182m0 3.961q-.181-.181-.181-.433t.181-.434t.434-.181t.434.181t.181.434t-.182.434t-.433.181t-.434-.182");
}

</style>
