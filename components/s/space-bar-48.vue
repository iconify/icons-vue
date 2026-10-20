<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbb7sw9yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbb7sw9yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:space-bar-48" /></template>
