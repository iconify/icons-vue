<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xalnqm_-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xalnqm_-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-20-bold" /></template>
