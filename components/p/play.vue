<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/s/sa0q3_jrq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu4ff0bvt"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="sa0q3_jrq"/></g></mask></defs><path mask="url(#SVGu4ff0bvt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:play" /></template>
