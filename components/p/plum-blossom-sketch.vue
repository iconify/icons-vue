<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o14n8cc4q.css';
import '../../css/r/ruzx8ebfp.css';
import '../../css/w/w7p7uxb7d.css';
import '../../css/z/zle4_sbjk.css';
import '../../css/o/ofm816o3p.css';
import '../../css/j/ju-940xbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o14n8cc4q wm-k"/><path class="ruzx8ebfp wm-k"/><path class="w7p7uxb7d wm-a"/><path class="wm-a zle4_sbjk"/><path class="ofm816o3p wm-a"/><circle class="ju-940xbu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plum-blossom-sketch" /></template>
