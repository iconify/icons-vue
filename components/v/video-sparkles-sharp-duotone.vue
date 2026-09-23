<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jdnpnfbih.css';
import '../../css/s/smhxg-b7v.css';
import '../../css/f/fmu2vzbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jdnpnfbih"/><path class="smhxg-b7v"/><path class="fmu2vzbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-sparkles-sharp-duotone" /></template>
