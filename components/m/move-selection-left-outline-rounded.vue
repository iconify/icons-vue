<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltmdxtb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:move-selection-left-outline-rounded" /></template>
<style>
.ltmdxtb4p {
  fill: currentColor;
  d: path("M4.616 17.039q-.672 0-1.144-.473Q3 16.094 3 15.423V8.577q0-.671.472-1.143q.472-.473 1.144-.473h6.846q.67 0 1.143.473q.472.472.472 1.143v6.846q0 .671-.472 1.143q-.472.473-1.143.473zm7.461-1.616V8.577q0-.27-.173-.442q-.173-.174-.442-.174H4.616q-.27 0-.443.173Q4 8.308 4 8.577v6.846q0 .27.173.443t.443.173h6.846q.269 0 .442-.174q.173-.173.173-.442m3.913 1.434q-.182-.182-.182-.434t.182-.433t.433-.182t.434.181t.181.434t-.181.434t-.434.181t-.433-.181m3.961 0q-.182-.182-.182-.434t.182-.433t.433-.182t.434.181t.182.434t-.182.434t-.434.181q-.251 0-.433-.181m0-4.423q-.182-.182-.182-.434t.182-.434t.433-.182t.434.182T21 12t-.182.434t-.434.182t-.433-.182m0-4.423q-.182-.182-.182-.434t.182-.434t.434-.181t.433.181t.182.434t-.182.434t-.434.181t-.433-.182m-3.962 0q-.181-.181-.181-.433t.182-.434t.433-.181t.434.181t.181.434t-.181.434t-.434.181t-.433-.182M8.038 12");
}

</style>
