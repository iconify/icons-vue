<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru1vegbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru1vegbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:minus-a" /></template>
