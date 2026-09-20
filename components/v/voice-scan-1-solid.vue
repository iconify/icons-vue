<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddnwvge2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ddnwvge2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-scan-1-solid" /></template>
