<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aebfkef-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aebfkef-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:text" /></template>
