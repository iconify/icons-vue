<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fh8rzobwg.css';
import '../../css/m/m7zug4ylz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJb7QgivB"><g class="v3_i3wktz"><path class="fh8rzobwg"/><path class="m7zug4ylz"/></g></mask></defs><path mask="url(#SVGJb7QgivB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:zoom-in" /></template>
