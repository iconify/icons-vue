<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktpu1oifd.css';
import '../../css/f/fo0_yzbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ktpu1oifd"/><path class="fo0_yzbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-data-20-bold" /></template>
