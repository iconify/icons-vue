<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo3owdb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-right-rounded" /></template>
<style>
.mo3owdb_b {
  fill: currentColor;
  d: path("M12.539 17.039q-.672 0-1.144-.473q-.472-.472-.472-1.143V8.577q0-.671.472-1.143q.472-.473 1.144-.473h6.846q.67 0 1.143.473q.472.472.472 1.143v6.846q0 .671-.472 1.143q-.472.473-1.144.473zM7.143 8.01q-.181-.181-.181-.433t.181-.434t.434-.181t.434.181t.181.434t-.182.434t-.433.181t-.434-.182m-3.528.182q-.252 0-.433-.182T3 7.578t.182-.434t.434-.181q.251 0 .433.181t.182.434t-.182.434t-.434.181m0 4.424q-.252 0-.433-.182T3 12t.182-.434t.434-.182q.251 0 .433.182t.182.434t-.182.434t-.434.182m0 4.422q-.252 0-.433-.181T3 16.423t.182-.433t.434-.182q.251 0 .433.181t.182.434t-.182.434t-.434.181m3.528-.181q-.181-.182-.181-.434t.181-.433t.434-.182t.434.181t.181.434t-.182.434t-.433.181t-.434-.181");
}

</style>
