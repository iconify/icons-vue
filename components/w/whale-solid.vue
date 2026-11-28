<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l21nl5osl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l21nl5osl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:whale-solid" /></template>
