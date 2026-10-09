<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx8zhcwih.css';
import '../../css/z/zcanx4ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wx8zhcwih"/><path class="zcanx4ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:uranium-20" /></template>
