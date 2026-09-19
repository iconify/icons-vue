<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzs7albyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzs7albyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:reduce" /></template>
