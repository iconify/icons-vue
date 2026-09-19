<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfd8llbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mfd8llbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:speech-language-therapy" /></template>
