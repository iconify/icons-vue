<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvtqlkbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtqlkbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:ruler-combined-outline" /></template>
