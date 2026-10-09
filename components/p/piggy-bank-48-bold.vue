<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq6x_qc-w.css';
import '../../css/d/d2omkm1_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dq6x_qc-w"/><path class="d2omkm1_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piggy-bank-48-bold" /></template>
