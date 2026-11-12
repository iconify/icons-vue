<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea24ebbtv.css';
import '../../css/i/il3gm6b7g.css';
import '../../css/c/cvwrb4bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGFfbq8ceP" x1="256.1" x2="256.1" y1="-96" y2="626.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="ea24ebbtv"/><stop offset="1" class="il3gm6b7g"/></linearGradient><path fill="url(#SVGFfbq8ceP)" class="cvwrb4bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:motioneye" /></template>
