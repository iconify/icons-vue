<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg_55xbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qg_55xbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:photography-light-mode-flash-on" /></template>
