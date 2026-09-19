<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-gz_3rkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-gz_3rkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:star" /></template>
