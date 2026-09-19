<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-m1_6ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8-m1_6ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:map" /></template>
