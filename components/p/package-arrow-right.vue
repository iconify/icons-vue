<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn82k1rbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn82k1rbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:package-arrow-right" /></template>
