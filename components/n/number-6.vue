<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0ta4dblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0ta4dblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6" /></template>
