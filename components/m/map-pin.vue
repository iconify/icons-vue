<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhklwbcuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhklwbcuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:map-pin" /></template>
