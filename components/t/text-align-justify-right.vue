<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhdnz2bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhdnz2bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-justify-right" /></template>
