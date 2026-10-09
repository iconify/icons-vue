<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy4vy0gsk.css';
import '../../css/v/vxoaqbnzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sy4vy0gsk"/><path class="vxoaqbnzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-substation-48" /></template>
