<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yogw2bbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yogw2bbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tablet-lock" /></template>
