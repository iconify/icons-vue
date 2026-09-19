<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv0sseb2v.css';
import '../../css/h/hgwopu5qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iv0sseb2v"/><path class="hgwopu5qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:sim-card-chip" /></template>
