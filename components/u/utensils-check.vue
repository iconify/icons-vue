<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obz2q_blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obz2q_blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:utensils-check" /></template>
