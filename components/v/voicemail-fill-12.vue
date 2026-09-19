<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/v/vn4okx2wl.css';
import '../../css/f/fge6z8bjk.css';
import '../../css/h/hytiksbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="flen3tbdj"><circle class="vn4okx2wl"/><circle class="fge6z8bjk"/><path class="hytiksbxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:voicemail-fill-12" /></template>
