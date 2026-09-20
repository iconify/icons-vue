<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/g/gnr3sl8iz.css';
import '../../css/q/q75lzwbjd.css';
import '../../css/a/aefmnnbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gnr3sl8iz"/><path class="q75lzwbjd"/><path class="aefmnnbnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-light-sharp-duotone" /></template>
