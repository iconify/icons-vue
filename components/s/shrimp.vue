<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qb1_c_8lg.css';
import '../../css/n/nwv7flbyu.css';
import '../../css/p/p14hulbxe.css';
import '../../css/y/y6qm2es2w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLHGnfbPy"><g class="ft5dv1b6b"><path class="qb1_c_8lg"/><path class="nwv7flbyu"/><path class="p14hulbxe"/><circle class="y6qm2es2w"/></g></mask></defs><path mask="url(#SVGLHGnfbPy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:shrimp" /></template>
