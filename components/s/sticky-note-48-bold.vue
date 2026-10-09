<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvvgk1bmy.css';
import '../../css/i/i0j09mbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvvgk1bmy"/><path class="i0j09mbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sticky-note-48-bold" /></template>
