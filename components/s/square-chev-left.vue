<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hiksrrvez.css';
import '../../css/x/xwlsu8bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hiksrrvez"/><path class="xwlsu8bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:square-chev-left" /></template>
