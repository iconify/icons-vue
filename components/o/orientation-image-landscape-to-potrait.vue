<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lux4zt8kc.css';
import '../../css/a/aikblhfzb.css';
import '../../css/p/pia5khlmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lux4zt8kc"/><path class="aikblhfzb"/><path class="pia5khlmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:orientation-image-landscape-to-potrait" /></template>
