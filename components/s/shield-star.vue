<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f025ktbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f025ktbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-star" /></template>
