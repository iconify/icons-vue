<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtc89hucc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1600};
const content = `<path class="gtc89hucc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:puzzle-piece" /></template>
