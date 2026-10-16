<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdlgrw2ra.css';
import '../../css/x/x-e0pwbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdlgrw2ra"/><path class="x-e0pwbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-half-48-bold" /></template>
