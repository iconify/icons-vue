<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mph6v1b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="mph6v1b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:martini-glass-citrus" /></template>
