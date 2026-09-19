<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/ond75zu1p.css';
import '../../css/g/gvnlxzqyt.css';
import '../../css/q/qp833-mnc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPcgNPcyR"><g class="aql7dnt-u"><path class="ond75zu1p"/><path class="gvnlxzqyt"/><path class="qp833-mnc"/></g></mask></defs><path mask="url(#SVGPcgNPcyR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shade" /></template>
