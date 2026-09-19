<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_-zvx93i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h_-zvx93i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:select-arrows" /></template>
