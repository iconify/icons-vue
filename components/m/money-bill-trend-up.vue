<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs254vjqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hs254vjqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-bill-trend-up" /></template>
