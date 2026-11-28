<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsz5y4byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsz5y4byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wine-star" /></template>
