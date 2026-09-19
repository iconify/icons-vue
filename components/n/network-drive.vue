<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/i/idtbkobxl.css';
import '../../css/l/lwpanqbve.css';
import '../../css/w/wfaf1ggge.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmIHPWbdb"><g class="aql7dnt-u"><path class="idtbkobxl"/><path class="lwpanqbve"/><path class="wfaf1ggge"/></g></mask></defs><path mask="url(#SVGmIHPWbdb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:network-drive" /></template>
