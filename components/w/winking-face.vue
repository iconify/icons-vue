<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/e/enhgg_9ct.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJwtGUdqY"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="enhgg_9ct"/></g></mask></defs><path mask="url(#SVGJwtGUdqY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:winking-face" /></template>
