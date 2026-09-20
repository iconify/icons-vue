<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thbz86bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thbz86bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:sudoku-bold" /></template>
