<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki0l8_bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ki0l8_bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticc-dash-dark" /></template>
