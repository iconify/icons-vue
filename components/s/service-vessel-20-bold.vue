<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elry085fn.css';
import '../../css/d/duddw2vqv.css';
import '../../css/y/yc0e9lbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="elry085fn"/><path class="duddw2vqv"/><path class="yc0e9lbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:service-vessel-20-bold" /></template>
