<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sndazvbnj.css';
import '../../css/h/hu6j50bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sndazvbnj"/><path class="hu6j50bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:subtitle" /></template>
