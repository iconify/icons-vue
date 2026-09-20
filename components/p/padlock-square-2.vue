<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inpjly4dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="inpjly4dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:padlock-square-2" /></template>
