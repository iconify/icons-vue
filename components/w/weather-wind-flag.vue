<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb7uilnfd.css';
import '../../css/a/assurkbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xb7uilnfd"/><path class="assurkbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-wind-flag" /></template>
