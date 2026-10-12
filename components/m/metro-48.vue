<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjes_2big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjes_2big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:metro-48" /></template>
