<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydce0w0ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydce0w0ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trophy-star-fill" /></template>
