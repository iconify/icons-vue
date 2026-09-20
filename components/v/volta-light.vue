<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw04xcb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":778,"height":222};
const content = `<path class="dw04xcb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:volta-light" /></template>
