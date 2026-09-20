<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k04p0xb8w.css';
import '../../css/m/m-bmedbph.css';
import '../../css/y/yre2wm67g.css';
import '../../css/v/vzs1ah3os.css';
import '../../css/f/f7azv0kip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k04p0xb8w"/><path class="m-bmedbph"/><path class="yre2wm67g"/><circle class="vzs1ah3os"/><path class="f7azv0kip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-perspective-linear" /></template>
