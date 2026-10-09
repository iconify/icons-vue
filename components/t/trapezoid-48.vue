<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bktgiibth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bktgiibth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trapezoid-48" /></template>
