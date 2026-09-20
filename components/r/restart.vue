<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq3x47b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wq3x47b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:restart" /></template>
