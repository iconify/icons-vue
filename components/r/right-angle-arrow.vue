<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxvt694xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxvt694xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:right-angle-arrow" /></template>
