<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntpl853ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ntpl853ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:pin" /></template>
