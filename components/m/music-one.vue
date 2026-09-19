<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/o4_dtfbdv.css';
import '../../css/e/e14b7qcgu.css';
import '../../css/e/e1444ccft.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCFI2PcYZ"><g class="v3_i3wktz"><path class="o4_dtfbdv"/><path class="e14b7qcgu"/><path clip-rule="evenodd" class="e1444ccft"/></g></mask></defs><path mask="url(#SVGCFI2PcYZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:music-one" /></template>
