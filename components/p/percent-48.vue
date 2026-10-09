<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmxox-big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lmxox-big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:percent-48" /></template>
