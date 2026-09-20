<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoq87o7cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xoq87o7cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wheelie-bin-and-drink-bottle-and-can" /></template>
