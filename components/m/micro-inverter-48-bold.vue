<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c876zybxx.css';
import '../../css/n/njny6bb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c876zybxx"/><path class="njny6bb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-inverter-48-bold" /></template>
