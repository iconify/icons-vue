<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1n2l3blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1n2l3blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:right-2-short-arrow" /></template>
