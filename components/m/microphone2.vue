<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/ankvxfc_w.css';
import '../../css/n/nyi1rb2hl.css';
import '../../css/z/zc46plbst.css';
import '../../css/i/i0kttw1zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="h01tyzbfu"><circle transform="rotate(38.27 11.663 5.118)" class="ankvxfc_w"/><path class="nyi1rb2hl"/><path class="zc46plbst"/><path class="i0kttw1zp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:microphone2" /></template>
