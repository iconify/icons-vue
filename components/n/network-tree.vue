<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/t/tbvgkhbgw.css';
import '../../css/a/a3gin5bio.css';
import '../../css/m/mgr1uablx.css';
import '../../css/m/m3btrlbai.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9qeXgc5x"><g class="wwvp95byt"><path class="tbvgkhbgw"/><path class="a3gin5bio"/><path class="mgr1uablx"/><path class="m3btrlbai"/></g></mask></defs><path mask="url(#SVG9qeXgc5x)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:network-tree" /></template>
