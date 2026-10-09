<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1-q2fbul.css';
import '../../css/w/wz1m72y3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s1-q2fbul"/><path class="wz1m72y3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pin-20-bold" /></template>
