<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twp1bxbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twp1bxbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:unsplash" /></template>
