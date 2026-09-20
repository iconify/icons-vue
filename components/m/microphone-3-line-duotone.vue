<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/guj5ndblb.css';
import '../../css/s/s8pml3bkm.css';
import '../../css/g/g3qc0bb8u.css';
import '../../css/n/nh-kspbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="guj5ndblb"/><path class="s8pml3bkm"/><path class="g3qc0bb8u"/><path class="nh-kspbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-3-line-duotone" /></template>
