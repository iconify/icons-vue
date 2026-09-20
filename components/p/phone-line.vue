<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vas90-bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vas90-bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-line" /></template>
