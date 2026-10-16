<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k50br_b8z.css';
import '../../css/t/t3e4vmwxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k50br_b8z"/><path class="t3e4vmwxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:superscript-20" /></template>
