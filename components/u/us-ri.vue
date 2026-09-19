<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/m/mm_wv7bbg.css';
import '../../css/b/bbp_r889d.css';
import '../../css/r/rtu3shd6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="mm_wv7bbg"/><path class="bbp_r889d"/><path class="rtu3shd6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:us-ri" /></template>
