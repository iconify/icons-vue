<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rizeqw8_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rizeqw8_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:up-arrow-square" /></template>
