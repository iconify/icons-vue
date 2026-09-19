<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/o5t226bvr.css';
import '../../css/d/ddygjdbod.css';
import '../../css/h/ha53tcbge.css';
import '../../css/c/cuu9dts4z.css';
import '../../css/x/xctod_4ic.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4tyNJcYu"><g class="ufeehvblu"><rect class="o5t226bvr"/><path class="ddygjdbod"/><path class="ha53tcbge"/><path class="cuu9dts4z"/><path class="xctod_4ic"/></g></mask></defs><path mask="url(#SVG4tyNJcYu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:record" /></template>
