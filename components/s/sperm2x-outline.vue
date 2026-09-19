<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs8xe8bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qs8xe8bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sperm2x-outline" /></template>
