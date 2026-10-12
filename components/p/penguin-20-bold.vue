<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3tyy5-9p.css';
import '../../css/u/u6c4ubc7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t3tyy5-9p"/><path class="u6c4ubc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penguin-20-bold" /></template>
