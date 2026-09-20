<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/g/g0wdbbh0b.css';
import '../../css/i/i3pcmrmmi.css';
import '../../css/k/k3wcmpbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g0wdbbh0b"/><path class="i3pcmrmmi"/><path clip-rule="evenodd" class="k3wcmpbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:radio-sharp-duotone" /></template>
