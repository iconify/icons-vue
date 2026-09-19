<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mm0oaabax.css';
import '../../css/u/u_r6ezb6m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeomlRcTD"><g class="v3_i3wktz"><path class="mm0oaabax"/><path class="u_r6ezb6m"/></g></mask></defs><path mask="url(#SVGeomlRcTD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:speed" /></template>
