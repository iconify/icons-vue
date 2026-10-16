<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpwlrrj0w.css';
import '../../css/v/vc4rurisx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jpwlrrj0w"/><path class="vc4rurisx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:silicon-20-bold" /></template>
