<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iceq1soan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iceq1soan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:travel-car-2" /></template>
