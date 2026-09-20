<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqv2x2bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqv2x2bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:space-line" /></template>
