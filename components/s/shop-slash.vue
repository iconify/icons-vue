<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfceo3lpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wfceo3lpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shop-slash" /></template>
