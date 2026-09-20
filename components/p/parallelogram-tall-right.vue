<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaz2rfbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xaz2rfbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:parallelogram-tall-right" /></template>
