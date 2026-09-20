<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz1j1t8jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xz1j1t8jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:split-vertical" /></template>
