<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx1c48bxn.css';
import '../../css/v/v2hw9tbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nx1c48bxn"/><path class="v2hw9tbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oven-48-bold" /></template>
