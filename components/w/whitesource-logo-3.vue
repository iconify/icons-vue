<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/mexdldrmp.css';
import '../../css/r/r0xlvib1h.css';
import '../../css/v/v9-8lib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="mexdldrmp"/><path class="r0xlvib1h"/><path class="v9-8lib4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:whitesource-logo-3" /></template>
