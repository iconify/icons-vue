<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf_7anmsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rf_7anmsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:star-medal-1-remix" /></template>
