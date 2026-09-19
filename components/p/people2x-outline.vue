<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrf9qacza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wrf9qacza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:people2x-outline" /></template>
