<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seg1y75pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="seg1y75pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:plastik" /></template>
