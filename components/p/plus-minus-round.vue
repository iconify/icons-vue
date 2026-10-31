<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdor-wx8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdor-wx8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plus-minus-round" /></template>
