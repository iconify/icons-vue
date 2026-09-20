<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1-gz_pwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-gz_pwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-s-line" /></template>
