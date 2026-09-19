<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/mxp84ibzr.css';
import '../../css/t/tnokb4_9i.css';
import '../../css/x/xxy4glkza.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFAGCHeXA"><g class="aql7dnt-u"><path class="mxp84ibzr"/><path class="tnokb4_9i"/><path class="xxy4glkza"/></g></mask></defs><path mask="url(#SVGFAGCHeXA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:push-door" /></template>
