<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hxivbubpu.css';
import '../../css/j/jgw8fgb3y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfpU5Mqnm"><g class="v3_i3wktz"><path class="hxivbubpu"/><path class="jgw8fgb3y"/></g></mask></defs><path mask="url(#SVGfpU5Mqnm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:order" /></template>
