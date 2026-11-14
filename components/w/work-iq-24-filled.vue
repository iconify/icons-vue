<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxox-762u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-24-filled" /></template>
<style>
.rxox-762u {
  fill: currentColor;
  d: path("M16.499 4.062a1.75 1.75 0 0 1 1.75 0l2.126 1.227q.142.083.273.178a3.25 3.25 0 0 1 1.351 2.637v6.865a4.98 4.98 0 0 0-2.999-1a5 5 0 0 0-4 2v-.219a1.75 1.75 0 1 0-3.5 0v6.5c0 .279.066.542.183.776a3.2 3.2 0 0 1-1.308-.417l-2.001-1.155a1.75 1.75 0 0 1-.87-1.513v-9.675c0-.625.334-1.203.875-1.516zM13.25 15a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m5.75-.03a4 4 0 0 1 3.295 6.264l.485.486a.75.75 0 0 1-1.06 1.06l-.49-.49A4 4 0 1 1 19 14.97m0 1.5a2.5 2.5 0 1 0 1.134 4.725l-.914-.914a.75.75 0 0 1 1.06-1.06l.925.924A2.5 2.5 0 0 0 19 16.47M10.375 1.392a3.25 3.25 0 0 1 3.25 0l2.254 1.3l-.13.07l-8.12 4.69a3.25 3.25 0 0 0-1.625 2.814v9.675q0 .074.004.147l-2.383-1.376A3.25 3.25 0 0 1 2 15.898V8.104c0-1.161.62-2.234 1.625-2.815z");
}

</style>
