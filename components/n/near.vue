<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu1cjp9dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu1cjp9dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:near" /></template>
