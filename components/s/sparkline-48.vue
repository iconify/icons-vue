<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu9cx5bea.css';
import '../../css/c/cnom9xbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vu9cx5bea"/><path class="cnom9xbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sparkline-48" /></template>
