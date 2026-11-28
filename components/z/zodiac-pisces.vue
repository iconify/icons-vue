<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i8g04wnih.css';
import '../../css/p/p9jlw9bmd.css';
import '../../css/n/npnurpite.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i8g04wnih"/><path class="p9jlw9bmd"/><path class="npnurpite"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-pisces" /></template>
