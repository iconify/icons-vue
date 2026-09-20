<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voc__pi4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="voc__pi4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-curve" /></template>
