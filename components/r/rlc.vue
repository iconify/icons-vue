<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ferdt9nin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ferdt9nin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:rlc" /></template>
