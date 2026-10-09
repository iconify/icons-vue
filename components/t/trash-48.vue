<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8qaagfdl.css';
import '../../css/t/teo_t3bjd.css';
import '../../css/y/yg0rsvfpa.css';
import '../../css/p/pbaroequs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8qaagfdl"/><path class="teo_t3bjd"/><path class="yg0rsvfpa"/><path class="pbaroequs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trash-48" /></template>
