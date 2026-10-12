<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzs0rf_ry.css';
import '../../css/s/sw8ci2hap.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzs0rf_ry"/><path class="sw8ci2hap"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tag-plus-48" /></template>
