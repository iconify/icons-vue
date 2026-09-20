<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/cgesq6bin.css';
import '../../css/v/vdy_02tyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="cgesq6bin"/><path class="vdy_02tyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-2" /></template>
