<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dwz2oyjim.css';
import '../../css/s/sbweck1kl.css';
import '../../css/u/ukbh2e6hq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dwz2oyjim"/><path class="sbweck1kl"/><path class="ukbh2e6hq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-sparkles-sharp-two-tone" /></template>
