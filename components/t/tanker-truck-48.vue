<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m35bxhbui.css';
import '../../css/q/q0uyhzb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m35bxhbui"/><path class="q0uyhzb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tanker-truck-48" /></template>
