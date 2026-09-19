<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/l1iy0ffsf.css';
import '../../css/g/gpho4gepl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGC4DXYCBl"><g class="v3_i3wktz"><path class="l1iy0ffsf"/><path class="gpho4gepl"/></g></mask></defs><path mask="url(#SVGC4DXYCBl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:umbrella-one" /></template>
