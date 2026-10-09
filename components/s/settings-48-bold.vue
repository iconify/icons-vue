<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mepm0bcky.css';
import '../../css/j/jsr_zti9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mepm0bcky"/><path class="jsr_zti9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:settings-48-bold" /></template>
