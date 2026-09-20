<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esa26dzqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esa26dzqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:railroad-metro-bold" /></template>
