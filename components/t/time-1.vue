<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnwl7-b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nnwl7-b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:time-1" /></template>
