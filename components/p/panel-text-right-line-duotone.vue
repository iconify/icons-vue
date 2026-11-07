<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lt87iveio.css';
import '../../css/m/migl5jbsu.css';
import '../../css/b/beaeuqbls.css';
import '../../css/i/ip-kvve8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lt87iveio"/><path class="migl5jbsu"/><path class="beaeuqbls"/><path class="ip-kvve8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-text-right-line-duotone" /></template>
