<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/ztur-t_2p.css';
import '../../css/n/nqiw-hxzo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGedoEBbPO"><g class="ft5dv1b6b"><path class="ztur-t_2p"/><path class="nqiw-hxzo"/></g></mask></defs><path mask="url(#SVGedoEBbPO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:server" /></template>
