<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuf17ubvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuf17ubvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:swap" /></template>
