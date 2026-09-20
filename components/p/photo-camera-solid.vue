<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb4lhrbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yb4lhrbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:photo-camera-solid" /></template>
