<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mdn8cibnw.css';
import '../../css/i/ifxdngbna.css';
import '../../css/p/p2xmk4byv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="mdn8cibnw"/><path class="ifxdngbna"/><path class="p2xmk4byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:speaker-1" /></template>
