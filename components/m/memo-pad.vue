<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ardbekbnv.css';
import '../../css/x/x7in55byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ardbekbnv"/><path class="x7in55byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:memo-pad" /></template>
