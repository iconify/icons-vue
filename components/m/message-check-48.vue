<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrurpboo.css';
import '../../css/t/tgs0aybnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dyrurpboo"/><path class="tgs0aybnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-check-48" /></template>
