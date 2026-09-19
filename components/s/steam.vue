<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylofclr8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ylofclr8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:steam" /></template>
