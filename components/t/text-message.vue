<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/v/vtx7wn82i.css';
import '../../css/z/zsp_ecctg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnHaUEbHG"><g class="hv130ab-t"><path class="vtx7wn82i"/><path class="zsp_ecctg"/></g></mask></defs><path mask="url(#SVGnHaUEbHG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:text-message" /></template>
