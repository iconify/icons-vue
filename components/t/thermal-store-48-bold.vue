<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epdku6b-c.css';
import '../../css/s/s7lyrq7xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="epdku6b-c"/><path class="s7lyrq7xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-store-48-bold" /></template>
