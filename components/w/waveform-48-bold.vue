<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0gim_b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n0gim_b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waveform-48-bold" /></template>
