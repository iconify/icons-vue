<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz0nizbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz0nizbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:virus" /></template>
