<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj610ot7w.css';
import '../../css/u/up6p_bbnh.css';
import '../../css/e/et771ymsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cj610ot7w"/><path class="up6p_bbnh"/><path class="et771ymsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:split-line" /></template>
