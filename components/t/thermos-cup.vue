<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/y91dc7fgl.css';
import '../../css/f/f13g7bbsq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGf1eZDeMa"><g class="v3_i3wktz"><path class="y91dc7fgl"/><path class="f13g7bbsq"/></g></mask></defs><path mask="url(#SVGf1eZDeMa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:thermos-cup" /></template>
