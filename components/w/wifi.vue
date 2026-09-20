<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/a/auv1wpb8c.css';
import '../../css/p/puhknjl3i.css';
import '../../css/s/sdyp_4liq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="auv1wpb8c"/><path class="puhknjl3i"/><path class="sdyp_4liq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:wifi" /></template>
