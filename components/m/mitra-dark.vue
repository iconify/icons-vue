<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vynof2yuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vynof2yuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitra-dark" /></template>
