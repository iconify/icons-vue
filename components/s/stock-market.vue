<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bw4ja6b0h.css';
import '../../css/a/aiajx7ljo.css';
import '../../css/b/b0___p7qg.css';
import '../../css/r/rle50jbed.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGV3aj1d2i"><g class="v3_i3wktz"><path class="bw4ja6b0h"/><path class="aiajx7ljo"/><path class="b0___p7qg"/><path class="rle50jbed"/></g></mask></defs><path mask="url(#SVGV3aj1d2i)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:stock-market" /></template>
