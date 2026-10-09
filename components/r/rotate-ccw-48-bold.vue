<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7pegcc2c.css';
import '../../css/q/qb0cveb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h7pegcc2c"/><path class="qb0cveb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-ccw-48-bold" /></template>
