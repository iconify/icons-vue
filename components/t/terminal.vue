<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpbz69bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1280};
const content = `<path class="xpbz69bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:terminal" /></template>
