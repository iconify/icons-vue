<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud8-gub-u.css';
import '../../css/d/da77vd8hl.css';
import '../../css/r/rrj52fbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ud8-gub-u"/><path class="da77vd8hl"/><path class="rrj52fbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-buoy-48" /></template>
