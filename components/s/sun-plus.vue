<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx7pxbcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx7pxbcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sun-plus" /></template>
