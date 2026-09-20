<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhtyav7tz.css';
import '../../css/k/kvketbp9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhtyav7tz"/><path class="kvketbp9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rice-ball-filled" /></template>
