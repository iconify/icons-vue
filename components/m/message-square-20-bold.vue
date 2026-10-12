<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvl7hibfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wvl7hibfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-square-20-bold" /></template>
