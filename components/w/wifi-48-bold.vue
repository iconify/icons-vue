<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5ad8vbal.css';
import '../../css/v/v3_ntib1p.css';
import '../../css/y/y50a790-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5ad8vbal"/><path class="v3_ntib1p"/><path class="y50a790-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-48-bold" /></template>
