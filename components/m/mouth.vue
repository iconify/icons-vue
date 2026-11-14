<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmougklqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mouth" /></template>
<style>
.pmougklqb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.877 12.417Q5.766 18.25 12 18.25q6.235 0 10.124-5.834q.015-.022.028-.046l-.019.033l-.009.013q-.08.121-.2.203t-.261.113Q18.207 13.5 12 13.5t-9.663-.768q-.141-.031-.26-.113q-.12-.081-.2-.202m20.233-.853q-4.264-5.97-8.597-4.526q-.03.01-.058.023L12 7.684l-1.455-.623q-.028-.013-.058-.023q-4.333-1.444-8.597 4.526q.085-.119.207-.197q.126-.08.273-.106t.293.007Q5.957 12 12 12t9.337-.732q.108-.024.218-.016t.213.048q.103.039.191.107q.087.067.151.157");
}

</style>
