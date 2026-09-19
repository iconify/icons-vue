<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f07qn6rfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f07qn6rfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:markdown" /></template>
