<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haa_wlj3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="haa_wlj3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:menu" /></template>
