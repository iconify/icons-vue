<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf93-kb8r.css';
import '../../css/q/qunbzgvvb.css';
import '../../css/i/iycln-b8i.css';
import '../../css/y/y-50ago-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG8MfK9diJ" x1="256" x2="256" y1="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="wf93-kb8r"/><stop offset="1" class="qunbzgvvb"/></linearGradient><circle fill="url(#SVG8MfK9diJ)" class="iycln-b8i"/><path class="y-50ago-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:syncthing" /></template>
