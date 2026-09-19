<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kspzgnbsg.css';
import '../../css/u/u_nsrq4io.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXE6zpcEE"><g class="ufeehvblu"><rect class="kspzgnbsg"/><path class="u_nsrq4io"/></g></mask></defs><path mask="url(#SVGXE6zpcEE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:terminal" /></template>
