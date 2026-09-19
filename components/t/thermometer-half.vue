<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hir5abctf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="hir5abctf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thermometer-half" /></template>
