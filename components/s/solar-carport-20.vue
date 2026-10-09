<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skan8zbga.css';
import '../../css/w/w879yqieg.css';
import '../../css/g/g5cv3vban.css';
import '../../css/u/uxaudcccd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="skan8zbga"/><path class="w879yqieg"/><path class="g5cv3vban"/><path class="uxaudcccd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-carport-20" /></template>
