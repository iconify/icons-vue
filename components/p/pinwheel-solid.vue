<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ark1bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i6ark1bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pinwheel-solid" /></template>
