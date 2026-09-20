<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbeq_z80i.css';
import '../../css/l/lm_iwebwk.css';
import '../../css/n/nsb6w10iq.css';
import '../../css/t/ttvgmtbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGLfEBd1fV" cx="3800.412" cy="5424.836" r="4986.692" gradientTransform="matrix(.09217 .00007 -.00007 .09926 -93.892 -282.725)" gradientUnits="userSpaceOnUse"><stop offset="0" class="fbeq_z80i"/><stop offset="1" class="lm_iwebwk"/></radialGradient><path fill="url(#SVGLfEBd1fV)" class="nsb6w10iq"/><path class="ttvgmtbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privatebin" /></template>
