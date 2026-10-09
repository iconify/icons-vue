<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl3t2kb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rl3t2kb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:paw-48" /></template>
