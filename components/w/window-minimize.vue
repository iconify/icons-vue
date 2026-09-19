<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2cffkbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2cffkbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:window-minimize" /></template>
