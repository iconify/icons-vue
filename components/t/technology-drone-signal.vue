<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdygn-ngl.css';
import '../../css/h/hq8skxj4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cdygn-ngl"/><path class="hq8skxj4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:technology-drone-signal" /></template>
