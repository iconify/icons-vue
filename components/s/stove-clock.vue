<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypnt1e9an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypnt1e9an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stove-clock" /></template>
