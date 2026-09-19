<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/r/r7egh7bcr.css';
import '../../css/d/d5cptp0zi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwYmErewy"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="r7egh7bcr"/><path class="d5cptp0zi"/></g></mask></defs><path mask="url(#SVGwYmErewy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:view-grid-list" /></template>
