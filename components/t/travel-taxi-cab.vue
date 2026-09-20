<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjrp9ib9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fjrp9ib9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:travel-taxi-cab" /></template>
