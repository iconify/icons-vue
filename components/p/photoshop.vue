<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kv45gzbce.css';
import '../../css/q/qh4w5dbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="kv45gzbce"/><path class="qh4w5dbmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:photoshop" /></template>
