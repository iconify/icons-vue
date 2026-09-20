<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xwcz-viev.css';
import '../../css/v/vr_ofdcez.css';
import '../../css/e/eudukmbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xwcz-viev"/><path class="vr_ofdcez"/><path clip-rule="evenodd" class="eudukmbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-outline" /></template>
