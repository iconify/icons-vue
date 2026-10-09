<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxy2tubhz.css';
import '../../css/m/mw2e6bc0g.css';
import '../../css/r/rm1abvbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rxy2tubhz"/><path class="mw2e6bc0g"/><path class="rm1abvbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-down-48-bold" /></template>
