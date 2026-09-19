<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz9d9ozsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz9d9ozsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:star" /></template>
