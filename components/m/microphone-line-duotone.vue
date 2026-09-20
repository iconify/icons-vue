<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/guj5ndblb.css';
import '../../css/s/szyabkg6c.css';
import '../../css/m/mc9d6_y9s.css';
import '../../css/n/nh-kspbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="szyabkg6c"/><path class="mc9d6_y9s"/><path class="nh-kspbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-line-duotone" /></template>
