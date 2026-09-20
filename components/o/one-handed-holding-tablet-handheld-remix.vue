<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azc24gbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="azc24gbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:one-handed-holding-tablet-handheld-remix" /></template>
