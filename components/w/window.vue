<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhrbmbcbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="zhrbmbcbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:window" /></template>
