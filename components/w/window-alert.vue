<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj5y0bbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5y0bbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:window-alert" /></template>
