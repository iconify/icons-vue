<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guaobubus.css';
import '../../css/i/i4xsl43pg.css';
import '../../css/y/y0aa2db-h.css';
import '../../css/q/q811zrblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="guaobubus"/><circle class="i4xsl43pg"/><path class="y0aa2db-h"/><path class="q811zrblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sunwithface" /></template>
