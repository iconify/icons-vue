<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h001g9p5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h001g9p5s primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-taurus-duotone" /></template>
