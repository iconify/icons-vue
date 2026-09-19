<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxcrvh-7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mxcrvh-7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notifications-paused" /></template>
