<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha1pxzb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha1pxzb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-down-left" /></template>
