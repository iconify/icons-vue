<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk0phibge.css';
import '../../css/e/e95vgl-bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0phibge"/><path class="e95vgl-bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:synclyrics-dark" /></template>
