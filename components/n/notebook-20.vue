<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flebhl8-j.css';
import '../../css/i/ioxwpib4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="flebhl8-j"/><path class="ioxwpib4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:notebook-20" /></template>
