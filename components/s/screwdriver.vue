<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dvsz9oblk.css';
import '../../css/p/pzopvfbeg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfNfIncUa"><g class="v3_i3wktz"><path class="dvsz9oblk"/><path class="pzopvfbeg"/></g></mask></defs><path mask="url(#SVGfNfIncUa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:screwdriver" /></template>
