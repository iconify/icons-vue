<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nukmbjz2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nukmbjz2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-menu-grid2x-outline" /></template>
