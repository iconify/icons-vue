<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcleu2o3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hcleu2o3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sketch" /></template>
