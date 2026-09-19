<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/z/z2o0ujiuj.css';
import '../../css/i/i18xl820u.css';
import '../../css/n/n2bughbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="z2o0ujiuj"/><circle class="i18xl820u"/><path class="n2bughbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:music-artist" /></template>
