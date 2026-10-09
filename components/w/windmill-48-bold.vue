<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxhd3fa8c.css';
import '../../css/l/l19np-bgg.css';
import '../../css/e/e3xg10aou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uxhd3fa8c"/><path class="l19np-bgg"/><path class="e3xg10aou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:windmill-48-bold" /></template>
