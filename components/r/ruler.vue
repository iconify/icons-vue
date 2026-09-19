<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1-2btbhm.css';
import '../../css/h/hkl-kbbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1-2btbhm"/><path class="hkl-kbbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:ruler" /></template>
