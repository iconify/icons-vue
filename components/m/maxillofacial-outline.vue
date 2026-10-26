<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv4ofb8wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xv4ofb8wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:maxillofacial-outline" /></template>
