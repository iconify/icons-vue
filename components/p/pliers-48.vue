<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc6qzlmiu.css';
import '../../css/k/kpa1g8jdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qc6qzlmiu"/><path class="kpa1g8jdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pliers-48" /></template>
