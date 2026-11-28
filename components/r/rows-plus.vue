<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yryw_xb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yryw_xb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rows-plus" /></template>
