<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4e4mlb2g.css';
import '../../css/o/owjt1z1hd.css';
import '../../css/p/pbc9w196e.css';
import '../../css/h/hs1eo5b-l.css';
import '../../css/b/bqv7lzboi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn1rgDeHL"><g class="u4e4mlb2g"><path class="owjt1z1hd"/><path class="pbc9w196e"/><path class="hs1eo5b-l"/><path class="bqv7lzboi"/></g></mask></defs><path mask="url(#SVGn1rgDeHL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rings" /></template>
