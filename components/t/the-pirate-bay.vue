<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5ugbtyd.css';
import '../../css/b/b9e_5bbiu.css';
import '../../css/b/b6lawlqju.css';
import '../../css/u/uxtrxm_nt.css';
import '../../css/v/vfr9u-oxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<filter id="SVGYjVSNduJ"><feGaussianBlur stdDeviation="2.8"/></filter><path filter="url(#SVGYjVSNduJ)" class="d-5ugbtyd"/><radialGradient id="SVGKzIrqtjw" cx="425.671" cy="41.248" r="261.656" gradientTransform="matrix(1.54075 .00151 .00111 -1.07785 -444.86 296.36)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b9e_5bbiu"/><stop offset=".41" class="b6lawlqju"/><stop offset="1" class="uxtrxm_nt"/></radialGradient><path fill="url(#SVGKzIrqtjw)" class="vfr9u-oxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-pirate-bay" /></template>
