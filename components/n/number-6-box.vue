<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq5ur9bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq5ur9bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-6-box" /></template>
