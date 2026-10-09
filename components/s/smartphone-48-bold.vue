<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw0sv1b2p.css';
import '../../css/o/ofyhu63mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iw0sv1b2p"/><path class="ofyhu63mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-48-bold" /></template>
