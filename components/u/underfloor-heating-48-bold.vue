<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cya2q_icv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cya2q_icv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:underfloor-heating-48-bold" /></template>
