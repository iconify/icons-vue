<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnfyskynu.css';
import '../../css/u/uhzk_qbaq.css';
import '../../css/x/xl_cnabsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGJeuH7K6i" x1="-48.712" x2="-47.692" y1="653.259" y2="653.259" gradientTransform="matrix(187.30569 450.9798 384.0336 -219.9575 -241602.61 165595.13)" gradientUnits="userSpaceOnUse"><stop offset="0" class="pnfyskynu"/><stop offset="1" class="uhzk_qbaq"/></linearGradient><path fill="url(#SVGJeuH7K6i)" class="xl_cnabsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextdns" /></template>
