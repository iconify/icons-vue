<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc1e_-bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="cc1e_-bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:truck" /></template>
