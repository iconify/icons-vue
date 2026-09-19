<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdmt-v1nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdmt-v1nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:satellite-1" /></template>
