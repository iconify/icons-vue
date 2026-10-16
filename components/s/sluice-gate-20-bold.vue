<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f__3z1bhu.css';
import '../../css/g/grgea9bwv.css';
import '../../css/n/nroycebvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f__3z1bhu"/><path class="grgea9bwv"/><path class="nroycebvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sluice-gate-20-bold" /></template>
