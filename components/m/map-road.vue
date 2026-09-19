<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/e/eo3-_3b1e.css';
import '../../css/f/f6z86b9cg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGM9RU2R1h"><g class="ufeehvblu"><path class="eo3-_3b1e"/><path class="f6z86b9cg"/></g></mask></defs><path mask="url(#SVGM9RU2R1h)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:map-road" /></template>
