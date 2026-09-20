<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf3rk1hgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf3rk1hgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rotated-off" /></template>
