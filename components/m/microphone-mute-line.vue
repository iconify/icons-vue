<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9831big.css';
import '../../css/a/as9o91e1g.css';
import '../../css/f/fgt-s_bka.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ic9831big"/><path class="as9o91e1g clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 fgt-s_bka"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:microphone-mute-line" /></template>
