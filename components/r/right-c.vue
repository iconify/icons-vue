<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/n/nvfk-ptxj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG31gDQb5R"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="nvfk-ptxj"/></g></mask></defs><path mask="url(#SVG31gDQb5R)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:right-c" /></template>
