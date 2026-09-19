<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntx9yf7qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntx9yf7qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:menu-kebab" /></template>
