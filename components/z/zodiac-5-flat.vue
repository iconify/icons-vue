<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_-jczb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h_-jczb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-5-flat" /></template>
