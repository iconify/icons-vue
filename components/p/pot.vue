<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs_zt8b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vs_zt8b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pot" /></template>
