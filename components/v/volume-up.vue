<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u50uczbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1472};
const content = `<path class="u50uczbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:volume-up" /></template>
