<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs1cxybvq.css';
import '../../css/v/v692yrxpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gs1cxybvq"/><path class="v692yrxpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seed-20-bold" /></template>
