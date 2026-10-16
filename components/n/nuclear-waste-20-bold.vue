<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs-k6d3fm.css';
import '../../css/c/c1--uvb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xs-k6d3fm"/><path class="c1--uvb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nuclear-waste-20-bold" /></template>
