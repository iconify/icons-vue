<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psoheuv8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="psoheuv8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:poison2x-outline" /></template>
