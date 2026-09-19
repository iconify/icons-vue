<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/b/bwpzy-b4l.css';
import '../../css/w/w6ufs9jem.css';
import '../../css/u/uts2ttbfw.css';
import '../../css/s/sunh8ec1l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHEPLKWXo"><g class="rohhhzb0l"><rect class="bwpzy-b4l"/><path class="w6ufs9jem"/><path class="uts2ttbfw"/><path class="sunh8ec1l"/></g></mask></defs><path mask="url(#SVGHEPLKWXo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:storage-card-two" /></template>
