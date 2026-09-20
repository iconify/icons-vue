<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxq2fbs4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxq2fbs4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scholarsome-light" /></template>
