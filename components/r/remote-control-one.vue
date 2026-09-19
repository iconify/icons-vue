<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f3vefubig.css';
import '../../css/k/ku608vbgm.css';
import '../../css/u/uhho6ibcr.css';
import '../../css/k/k62t2mcjl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCL1YCbGf"><g class="ft5dv1b6b"><path class="f3vefubig"/><path class="ku608vbgm"/><circle class="uhho6ibcr"/><circle class="k62t2mcjl"/></g></mask></defs><path mask="url(#SVGCL1YCbGf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:remote-control-one" /></template>
