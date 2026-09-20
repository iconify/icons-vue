<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhla2-b5p.css';
import '../../css/r/r2gwrbc_m.css';
import '../../css/o/olx8frbln.css';
import '../../css/p/p-0gvwbqy.css';
import '../../css/d/dr--31bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhla2-b5p"/><path class="r2gwrbc_m"/><path class="olx8frbln"/><path class="p-0gvwbqy"/><path class="dr--31bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:musical-score" /></template>
