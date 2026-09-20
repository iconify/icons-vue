<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrrrx-r_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yrrrx-r_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:weight" /></template>
