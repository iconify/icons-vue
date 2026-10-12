<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxr2twvpp.css';
import '../../css/e/ebng-2bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cxr2twvpp"/><path class="ebng-2bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pill-bottle-48-bold" /></template>
