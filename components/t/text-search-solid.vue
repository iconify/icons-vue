<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy65659er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy65659er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-search-solid" /></template>
