<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwg3kp-2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dwg3kp-2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:star-small-outline" /></template>
