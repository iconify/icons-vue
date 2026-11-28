<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybu19b1aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybu19b1aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:smartphone-x" /></template>
