<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwy-ycizl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nwy-ycizl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:opt" /></template>
