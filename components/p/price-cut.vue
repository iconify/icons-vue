<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gasgx252x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gasgx252x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:price-cut" /></template>
