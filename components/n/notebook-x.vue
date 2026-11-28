<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7xx2zbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7xx2zbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:notebook-x" /></template>
