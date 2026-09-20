<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5pwa2bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t5pwa2bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:select-circle-area-1-remix" /></template>
