<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djqd47bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="djqd47bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:pencil" /></template>
