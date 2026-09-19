<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/k/kx04fnnhl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGD70y6cqT"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="kx04fnnhl"/></g></mask></defs><path mask="url(#SVGD70y6cqT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sliding-horizontal" /></template>
