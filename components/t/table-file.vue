<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kz767lbkx.css';
import '../../css/h/hrh2izb_y.css';
import '../../css/f/f2jxhypno.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCpDiAduO"><g class="ufeehvblu"><path class="kz767lbkx"/><path class="hrh2izb_y"/><path class="f2jxhypno"/></g></mask></defs><path mask="url(#SVGCpDiAduO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:table-file" /></template>
