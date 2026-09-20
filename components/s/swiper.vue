<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz1f_bc-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1f_bc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:swiper" /></template>
