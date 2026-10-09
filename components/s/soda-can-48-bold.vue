<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj2y_bb9h.css';
import '../../css/u/u01yqubev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tj2y_bb9h"/><path class="u01yqubev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soda-can-48-bold" /></template>
