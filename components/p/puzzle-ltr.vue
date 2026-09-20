<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dccqsobpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dccqsobpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:puzzle-ltr" /></template>
