<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p54j5rcsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p54j5rcsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:memorial-14" /></template>
