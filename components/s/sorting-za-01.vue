<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgbsv---w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgbsv---w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-za-01" /></template>
