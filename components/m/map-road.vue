<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kca82-bbm.css';
import '../../css/p/pl_657gxa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFawpXbsf"><g class="v3_i3wktz"><path class="kca82-bbm"/><path class="pl_657gxa"/></g></mask></defs><path mask="url(#SVGFawpXbsf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:map-road" /></template>
