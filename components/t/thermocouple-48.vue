<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_44j831n.css';
import '../../css/f/fjz8aybha.css';
import '../../css/m/mib1oqjfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m_44j831n"/><path class="fjz8aybha"/><path class="mib1oqjfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermocouple-48" /></template>
