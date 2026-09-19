<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/m/m-_faca9a.css';
import '../../css/y/ybvr_gb5s.css';
import '../../css/f/f0281acph.css';
import '../../css/f/fuc7djkee.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhOkrxdlG"><g class="rohhhzb0l"><circle class="m-_faca9a"/><path class="ybvr_gb5s"/><circle class="f0281acph"/><path class="fuc7djkee"/></g></mask></defs><path mask="url(#SVGhOkrxdlG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-search-one" /></template>
