<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9eadlwgv.css';
import '../../css/q/q_m60h3vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9eadlwgv"/><path class="q_m60h3vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-storage-48-bold" /></template>
