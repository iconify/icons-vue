<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-c0ls6qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w-c0ls6qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spades-symbol" /></template>
