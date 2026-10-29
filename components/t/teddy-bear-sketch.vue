<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p1c4ohbig.css';
import '../../css/k/kc999gbve.css';
import '../../css/z/z8mp29m8t.css';
import '../../css/m/m26_tac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p1c4ohbig wm-k"/><path class="kc999gbve wm-a"/><circle class="z8mp29m8t"/><circle class="m26_tac-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:teddy-bear-sketch" /></template>
