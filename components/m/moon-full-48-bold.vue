<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdlgrw2ra.css';
import '../../css/o/o91sag11f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="o91sag11f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-full-48-bold" /></template>
