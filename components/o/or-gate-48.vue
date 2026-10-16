<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdb70jjls.css';
import '../../css/t/tfdzc8bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wdb70jjls"/><path class="tfdzc8bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:or-gate-48" /></template>
