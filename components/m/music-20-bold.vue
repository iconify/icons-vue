<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbbi_6vwc.css';
import '../../css/x/xo70x1c7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qbbi_6vwc"/><path class="xo70x1c7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:music-20-bold" /></template>
