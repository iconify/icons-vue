<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3343rbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w3343rbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:regionalindicatorp" /></template>
