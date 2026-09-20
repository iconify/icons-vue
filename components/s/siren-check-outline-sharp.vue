<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6a8jib9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:siren-check-outline-sharp" /></template>
<style>
.m6a8jib9t {
  fill: currentColor;
  d: path("M14.347 20.71q-1.25-1.25-1.25-3.056t1.25-3.057t3.057-1.25t3.057 1.25q1.25 1.251 1.25 3.057t-1.25 3.056t-3.057 1.251t-3.057-1.25m2.351-1.172l3.148-3.143l-.627-.627l-2.521 2.51l-1.11-1.11l-.626.633zm-8.025-6.597h1v-2.807q0-.952.684-1.63q.683-.678 1.643-.678v-1q-1.38 0-2.354.964q-.973.963-.973 2.344zM3 20v-4.75h2.827v-5.115q0-2.564 1.797-4.35T12 4t4.376 1.786t1.797 4.349v.863q-.125-.012-.244-.014q-.118-.003-.256-.003t-.256.003q-.119.002-.244.014v-.863q0-2.152-1.514-3.644T11.997 5t-3.66 1.491t-1.51 3.644v5.115h4.329q-.09.244-.173.485q-.083.24-.139.515H4V19h6.844q.056.275.12.516q.063.24.153.484z");
}

</style>
