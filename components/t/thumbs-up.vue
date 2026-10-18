<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo45pacgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo45pacgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thumbs-up" /></template>
