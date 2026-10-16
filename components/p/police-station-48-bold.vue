<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf6_mjbtg.css';
import '../../css/r/rpy7blvsf.css';
import '../../css/y/yc61-tb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gf6_mjbtg"/><path class="rpy7blvsf"/><path class="yc61-tb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:police-station-48-bold" /></template>
