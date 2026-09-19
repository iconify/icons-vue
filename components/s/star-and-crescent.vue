<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnu6byhtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tnu6byhtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:star-and-crescent" /></template>
