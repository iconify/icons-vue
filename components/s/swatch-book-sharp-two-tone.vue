<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xntt-lbbf.css';
import '../../css/m/mj1i6js7i.css';
import '../../css/e/em8goyshd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xntt-lbbf"/><path class="mj1i6js7i"/><path class="em8goyshd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swatch-book-sharp-two-tone" /></template>
