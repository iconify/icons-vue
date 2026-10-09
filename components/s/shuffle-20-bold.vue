<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg5px6bdo.css';
import '../../css/u/ux46odduj.css';
import '../../css/y/yix08vbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xg5px6bdo"/><path class="ux46odduj"/><path class="yix08vbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shuffle-20-bold" /></template>
