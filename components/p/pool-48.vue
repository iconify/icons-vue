<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-eh9wb_p.css';
import '../../css/q/q3uapjb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-eh9wb_p"/><path class="q3uapjb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pool-48" /></template>
