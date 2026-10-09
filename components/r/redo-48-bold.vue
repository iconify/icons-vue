<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhdbk79fo.css';
import '../../css/q/qcnda-9od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mhdbk79fo"/><path class="qcnda-9od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:redo-48-bold" /></template>
