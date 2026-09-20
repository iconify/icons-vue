<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkaqp8bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkaqp8bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:seedling-line" /></template>
