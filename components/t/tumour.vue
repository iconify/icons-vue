<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shyli0b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tumour" /></template>
<style>
.shyli0b8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.853 2.015q2.156-.432 3.556.835q.932.843 1.092 1.968q1.531-.162 2.743.899q1.437 1.258 1.118 3.143q1.547.972 1.606 2.993q.059 2.003-1.36 3.007q.357 1.932-.962 3.367q-1.315 1.428-3.176 1.147q-.796 1.718-2.772 2.17q-2.011.459-3.334-.815q-1.615.882-3.391.08q-1.896-.856-1.988-2.737q-1.805-.605-2.388-2.473q-.59-1.889.64-3.199q-1.022-1.595-.276-3.432q.762-1.875 2.587-2.165q.248-1.751 1.796-2.746q1.45-.932 2.942-.534q.501-1.159 1.477-1.485q.044-.014.09-.023M12.5 9q0 1.75 1.75 1.75T16 9t-1.75-1.75T12.5 9M9 12.25q-2.25 0-2.25 2.25T9 16.75t2.25-2.25T9 12.25");
}

</style>
