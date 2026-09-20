<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe8ilbs_y.css';
import '../../css/i/i-jzrbbnk.css';
import '../../css/r/r0ixaf-0p.css';
import '../../css/c/conjjsbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":367.5,"height":45};
const content = `<path class="pe8ilbs_y"/><path class="i-jzrbbnk"/><path class="r0ixaf-0p"/><path class="conjjsbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:productboard-dark" /></template>
