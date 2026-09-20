<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzm8x023o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gzm8x023o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:sticker" /></template>
