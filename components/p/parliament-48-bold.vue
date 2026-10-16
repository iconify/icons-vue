<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5b5yobqi.css';
import '../../css/e/e7boe99qi.css';
import '../../css/o/os4jmsbas.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5b5yobqi"/><path class="e7boe99qi"/><path class="os4jmsbas"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parliament-48-bold" /></template>
