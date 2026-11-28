<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aksmz6bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aksmz6bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:network-lock" /></template>
