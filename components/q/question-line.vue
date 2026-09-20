<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp1_bxbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp1_bxbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:question-line" /></template>
