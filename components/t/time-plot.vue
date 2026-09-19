<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrrsmlbdl.css';
import '../../css/o/ow0kcdcgg.css';
import '../../css/p/p_c34mhur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hrrsmlbdl"/><path class="ow0kcdcgg"/><path class="p_c34mhur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:time-plot" /></template>
