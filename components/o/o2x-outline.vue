<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_gbwm76b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w_gbwm76b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:o2x-outline" /></template>
