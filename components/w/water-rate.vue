<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/yjb0_8b7z.css';
import '../../css/z/zu_quob4e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCK9oCgcW"><g class="ufeehvblu"><path class="yjb0_8b7z"/><path class="zu_quob4e"/></g></mask></defs><path mask="url(#SVGCK9oCgcW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:water-rate" /></template>
