<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6_diewni.css';
import '../../css/s/s2uksm1sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6_diewni"/><path class="s2uksm1sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-sparkle-48-bold" /></template>
