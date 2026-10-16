<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcnvp-btz.css';
import '../../css/y/ygre9pbqx.css';
import '../../css/t/t75ay3btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lcnvp-btz"/><path class="ygre9pbqx"/><path class="t75ay3btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spring-balance-20" /></template>
