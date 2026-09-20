<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6pioblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pd6pioblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:swap" /></template>
