<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxx2r1bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxx2r1bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkles-48" /></template>
