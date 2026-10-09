<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jijaykbcd.css';
import '../../css/u/uylaeij1i.css';
import '../../css/y/y1e_v1sal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jijaykbcd"/><path class="uylaeij1i"/><path class="y1e_v1sal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-cursor-20-bold" /></template>
