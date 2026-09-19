<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmc733baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hmc733baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-zoom-outline" /></template>
