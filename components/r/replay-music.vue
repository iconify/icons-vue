<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bc32plywa.css';
import '../../css/j/j2oelba8n.css';
import '../../css/f/fw48gdx3v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGB8rdedOA"><g class="v3_i3wktz"><path class="bc32plywa"/><path class="j2oelba8n"/><path class="fw48gdx3v"/></g></mask></defs><path mask="url(#SVGB8rdedOA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:replay-music" /></template>
