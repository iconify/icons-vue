<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa3c4bb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pa3c4bb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:newline-rtl" /></template>
