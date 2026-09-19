<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3x82etzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x3x82etzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:rss" /></template>
