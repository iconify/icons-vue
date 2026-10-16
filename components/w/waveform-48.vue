<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4pi18-ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4pi18-ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waveform-48" /></template>
