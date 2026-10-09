<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2wnij_0h.css';
import '../../css/o/o6j5_ubif.css';
import '../../css/l/lu5ol8bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2wnij_0h"/><path class="o6j5_ubif"/><path class="lu5ol8bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-station-48-bold" /></template>
