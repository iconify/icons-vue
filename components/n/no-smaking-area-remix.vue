<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccd73rb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ccd73rb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:no-smaking-area-remix" /></template>
