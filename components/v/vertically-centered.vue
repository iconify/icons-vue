<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/m/mhwosdh5o.css';
import '../../css/x/xpua17bdp.css';
import '../../css/p/ple3qktap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="mhwosdh5o"/><rect class="xpua17bdp"/><path class="ple3qktap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:vertically-centered" /></template>
