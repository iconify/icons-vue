<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulzgxb59r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulzgxb59r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swipe-two-fingers-down-gesture" /></template>
