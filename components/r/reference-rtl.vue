<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha4ba9bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ha4ba9bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:reference-rtl" /></template>
