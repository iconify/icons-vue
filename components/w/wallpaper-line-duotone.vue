<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m9lr-xbek.css';
import '../../css/f/f2-h4iwhz.css';
import '../../css/u/urw2-mb8r.css';
import '../../css/y/ybw0md_9h.css';
import '../../css/h/hrmgh_hcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m9lr-xbek"/><path class="f2-h4iwhz"/><path class="urw2-mb8r"/><circle class="ybw0md_9h"/><path class="hrmgh_hcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallpaper-line-duotone" /></template>
