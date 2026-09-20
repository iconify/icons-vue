<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz1d529op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uz1d529op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:network" /></template>
