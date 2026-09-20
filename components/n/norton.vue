<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbrk8cblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrk8cblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:norton" /></template>
