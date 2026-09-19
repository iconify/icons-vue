<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/ff066bcmc.css';
import '../../css/w/wrlqzdago.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAGAFydaD"><g class="aql7dnt-u"><path class="ff066bcmc"/><path class="wrlqzdago"/></g></mask></defs><path mask="url(#SVGAGAFydaD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:map-draw" /></template>
