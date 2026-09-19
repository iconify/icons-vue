<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qc5yn2ygv.css';
import '../../css/y/yg4vlgrtx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFEeZHd1I"><g class="aql7dnt-u"><path class="qc5yn2ygv"/><path class="yg4vlgrtx"/></g></mask></defs><path mask="url(#SVGFEeZHd1I)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:micro-sd" /></template>
