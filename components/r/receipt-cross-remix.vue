<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdt7z-kws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kdt7z-kws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:receipt-cross-remix" /></template>
