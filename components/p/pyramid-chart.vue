<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwhhac4gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwhhac4gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pyramid-chart" /></template>
