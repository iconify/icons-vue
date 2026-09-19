<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrk6lbcgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yrk6lbcgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:page-left-solid" /></template>
