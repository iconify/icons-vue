<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp5ltcqbw.css';
import '../../css/w/wsnuap-ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVG42U0UdPS" viewBox="0 0 342 234"><path class="bp5ltcqbw"/></symbol></defs><use width="342" height="234" href="#SVG42U0UdPS" transform="translate(85 139)"/><path class="wsnuap-ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:wind-beaufort-0" /></template>
