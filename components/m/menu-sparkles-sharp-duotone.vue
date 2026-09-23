<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/ve--dvbvr.css';
import '../../css/s/sbweck1kl.css';
import '../../css/s/skqfcdqhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ve--dvbvr"/><path class="sbweck1kl"/><path class="skqfcdqhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:menu-sparkles-sharp-duotone" /></template>
