<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/d/du6ly7_6u.css';
import '../../css/l/l_zb0kbii.css';
import '../../css/n/ni471xbpa.css';
import '../../css/q/qlrywpd7k.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRVADRczg"><g class="gopnm44um"><ellipse class="du6ly7_6u"/><path class="l_zb0kbii"/><circle class="ni471xbpa"/><circle class="qlrywpd7k"/></g></mask></defs><path mask="url(#SVGRVADRczg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:soap-bubble" /></template>
