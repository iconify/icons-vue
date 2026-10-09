<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd10_3lgv.css';
import '../../css/c/czm4jwrva.css';
import '../../css/j/jih-r1b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fd10_3lgv"/><path class="czm4jwrva"/><path class="jih-r1b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webcam-48" /></template>
