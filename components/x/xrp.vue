<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycpa7yb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ycpa7yb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xrp" /></template>
