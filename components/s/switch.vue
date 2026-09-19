<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjbqqpizg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mjbqqpizg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:switch" /></template>
