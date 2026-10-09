<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jea-yh2jg.css';
import '../../css/d/dxyc4p_3e.css';
import '../../css/q/q73kfvgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jea-yh2jg"/><path class="dxyc4p_3e"/><path class="q73kfvgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:package-20-bold" /></template>
