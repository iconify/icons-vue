<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/c/cxxtcrb-r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGshujsUor"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="cxxtcrb-r"/></g></mask></defs><path mask="url(#SVGshujsUor)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:slightly-smiling-face" /></template>
