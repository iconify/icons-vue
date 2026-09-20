<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz_1252xr.css';
import '../../css/o/ob96or34g.css';
import '../../css/h/hsh8eosbs.css';
import '../../css/o/oq92ix4yp.css';
import '../../css/e/ed76xxe-l.css';
import '../../css/i/itl748bnl.css';
import '../../css/g/gdlzvwbrq.css';
import '../../css/e/e-t7yp20u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz_1252xr"/><path class="ob96or34g"/><path class="hsh8eosbs"/><path class="oq92ix4yp"/><path class="ed76xxe-l"/><path class="itl748bnl"/><path class="gdlzvwbrq"/><path class="e-t7yp20u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vela" /></template>
