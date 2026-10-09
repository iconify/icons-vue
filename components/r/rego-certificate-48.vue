<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuvdc2bma.css';
import '../../css/u/u04sb4b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yuvdc2bma"/><path class="u04sb4b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rego-certificate-48" /></template>
