<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq8_d-bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pin-end-sharp" /></template>
<style>
.dq8_d-bpk {
  fill: currentColor;
  d: path("M3 19V5h18v6.73h-1V6H4v12h9.73v1zm11.662-4.625L10.5 10.214v2.936h-1V8.5h4.65v1h-2.961l4.18 4.162zM18.577 19q-1.01 0-1.716-.707t-.707-1.716t.707-1.716t1.716-.707t1.716.707t.707 1.716t-.707 1.716t-1.716.707");
}

</style>
