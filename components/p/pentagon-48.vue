<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpbyx1ete.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpbyx1ete"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pentagon-48" /></template>
