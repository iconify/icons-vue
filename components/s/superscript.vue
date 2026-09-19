<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpeggtb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpeggtb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:superscript" /></template>
