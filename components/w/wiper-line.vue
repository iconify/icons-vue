<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs6abtbab.css';
import '../../css/y/y0euu7b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs6abtbab"/><path class="y0euu7b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wiper-line" /></template>
