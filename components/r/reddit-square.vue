<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vndabwbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vndabwbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:reddit-square" /></template>
