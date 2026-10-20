<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvbik02p.css';
import '../../css/n/nhbo4cseo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvbik02p"/><path class="nhbo4cseo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-question-20-bold" /></template>
