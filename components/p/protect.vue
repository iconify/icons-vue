<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gj7m2tbbh.css';
import '../../css/o/omd-qi_-c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGM7aMbcQo"><g class="v3_i3wktz"><path class="gj7m2tbbh"/><path class="omd-qi_-c"/></g></mask></defs><path mask="url(#SVGM7aMbcQo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:protect" /></template>
