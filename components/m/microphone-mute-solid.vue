<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic9831big.css';
import '../../css/a/aujrlr7yd.css';
import '../../css/o/o4nndobyg.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 ic9831big"/><path class="aujrlr7yd clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 o4nndobyg"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:microphone-mute-solid" /></template>
