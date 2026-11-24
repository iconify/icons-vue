<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ywrqi0hwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:zed-icon" /></template>
<style>
.ywrqi0hwr {
  d: path("M24 16a8 8 0 0 0-8 8v176H0V24C0 10.745 10.745 0 24 0h214.343c10.69 0 16.045 12.926 8.485 20.485L114.813 152.5H152V136h16v20.5c0 6.627-5.373 12-12 12H98.812l-27.5 27.5H196V96h16v100c0 8.836-7.164 16-16 16H55.314l-28 28H232a8 8 0 0 0 8-8V56h16v176c0 13.254-10.746 24-24 24H17.657c-10.691 0-16.045-12.926-8.485-20.486L140.686 104H104v16H88v-20c0-6.628 5.372-12 12-12h56.686l28-28H60v100H44V60c0-8.837 7.163-16 16-16h140.686l28-28z");
}

</style>
