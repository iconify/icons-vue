<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu797ubab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu797ubab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:the-odin-project" /></template>
