<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zvkp0cb3v.css';
import '../../css/h/h1rmlkb4z.css';
import '../../css/t/tofdy-80v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTCftzbBY"><g class="v3_i3wktz"><path class="zvkp0cb3v"/><path class="h1rmlkb4z"/><path class="tofdy-80v"/></g></mask></defs><path mask="url(#SVGTCftzbBY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shutter-priority" /></template>
