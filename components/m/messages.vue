<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/u/ua-z8vb0h.css';
import '../../css/l/lds1gmbsi.css';
import '../../css/g/gpeukobmo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgyn6Nddu"><g class="rohhhzb0l"><path class="ua-z8vb0h"/><path class="lds1gmbsi"/><path class="gpeukobmo"/></g></mask></defs><path mask="url(#SVGgyn6Nddu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:messages" /></template>
