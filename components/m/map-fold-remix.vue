<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itw0z-bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="itw0z-bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:map-fold-remix" /></template>
