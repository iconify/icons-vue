<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fh8rzobwg.css';
import '../../css/i/i0u2ubbtx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxa0n2cLp"><g class="v3_i3wktz"><path class="fh8rzobwg"/><path class="i0u2ubbtx"/></g></mask></defs><path mask="url(#SVGxa0n2cLp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:zoom-out" /></template>
