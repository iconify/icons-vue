<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d75b1zbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d75b1zbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:minimize-1" /></template>
