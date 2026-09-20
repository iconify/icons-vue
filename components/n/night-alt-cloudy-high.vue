<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_kpqtr2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="u_kpqtr2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-alt-cloudy-high" /></template>
