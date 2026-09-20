<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/t/thkopl_9m.css';
import '../../css/m/mmgrvcb7f.css';
import '../../css/g/g67_oophs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="thkopl_9m"/><path class="mmgrvcb7f"/><path class="g67_oophs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:umbrella-off-sharp-duotone" /></template>
