<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv21g9bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dv21g9bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:text-dir-rtl" /></template>
