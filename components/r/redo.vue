<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2j7_lbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k2j7_lbyc st0"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:redo" /></template>
