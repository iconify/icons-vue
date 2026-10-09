<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5xk1zbsn.css';
import '../../css/g/g60bl7rlr.css';
import '../../css/m/mtjikgb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l5xk1zbsn"/><path class="g60bl7rlr"/><path class="mtjikgb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-street-light-20-bold" /></template>
