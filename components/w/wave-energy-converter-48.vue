<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpgv9kb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fpgv9kb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wave-energy-converter-48" /></template>
