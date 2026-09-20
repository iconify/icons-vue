<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p87vsdboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p87vsdboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:walmart-dark" /></template>
