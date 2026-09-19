<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmd2ivbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xmd2ivbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toilet" /></template>
