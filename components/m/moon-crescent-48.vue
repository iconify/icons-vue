<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_zzgnel.css';
import '../../css/m/ml2cy1-1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="ml2cy1-1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-crescent-48" /></template>
