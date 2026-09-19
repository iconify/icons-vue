<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-z8ibrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cu-z8ibrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:neuro-surgery2x-outline" /></template>
