<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub4cgse3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub4cgse3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:stream-off" /></template>
