<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc5lfdlew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hc5lfdlew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-small2x-outline" /></template>
