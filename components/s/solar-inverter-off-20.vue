<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-z8u6wyr.css';
import '../../css/l/l9s722bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c-z8u6wyr"/><path class="l9s722bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-off-20" /></template>
