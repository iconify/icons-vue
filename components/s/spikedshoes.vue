<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsfne-b7l.css';
import '../../css/o/o1w6bqbbl.css';
import '../../css/k/kw24-ibsp.css';
import '../../css/k/kw37wvbai.css';
import '../../css/i/icv4h0htq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpSUqIc3L"><g class="nsfne-b7l"><path class="o1w6bqbbl"/><path class="kw24-ibsp"/><path class="kw37wvbai"/><path class="icv4h0htq"/></g></mask></defs><path mask="url(#SVGpSUqIc3L)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:spikedshoes" /></template>
