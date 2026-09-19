<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5b61ccaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="b5b61ccaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-letterboxd" /></template>
