<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulzixyb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulzixyb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-right-01" /></template>
