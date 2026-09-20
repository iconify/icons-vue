<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq-lkn43o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qq-lkn43o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:voice-scan-1-remix" /></template>
