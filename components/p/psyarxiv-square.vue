<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5rwvjb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p5rwvjb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:psyarxiv-square" /></template>
