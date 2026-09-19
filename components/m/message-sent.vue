<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qgceg4vvs.css';
import '../../css/x/xr1cpub8x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKM1ffcso"><g class="aql7dnt-u"><path class="qgceg4vvs"/><path class="xr1cpub8x"/></g></mask></defs><path mask="url(#SVGKM1ffcso)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:message-sent" /></template>
