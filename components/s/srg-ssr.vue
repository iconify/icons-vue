<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwn6c4bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwn6c4bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:srg-ssr" /></template>
