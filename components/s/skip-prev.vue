<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4x9_2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4x9_2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:skip-prev" /></template>
