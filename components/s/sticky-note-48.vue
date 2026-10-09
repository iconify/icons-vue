<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_3b78b5d.css';
import '../../css/w/w80p7wbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l_3b78b5d"/><path class="w80p7wbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticky-note-48" /></template>
