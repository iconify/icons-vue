<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/n-h32kbxs.css';
import '../../css/g/ggkj7yboh.css';
import '../../css/i/ikt6m-tna.css';
import '../../css/a/asnrasl1d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMx9Ojb7e"><g class="ufeehvblu"><path class="n-h32kbxs"/><path class="ggkj7yboh"/><path class="ikt6m-tna"/><path class="asnrasl1d"/></g></mask></defs><path mask="url(#SVGMx9Ojb7e)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tv-one" /></template>
