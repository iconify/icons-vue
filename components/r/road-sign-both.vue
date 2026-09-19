<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/s4zvpcc_e.css';
import '../../css/g/gr78cdb7s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcRltieMe"><g class="v3_i3wktz"><path class="s4zvpcc_e"/><path class="gr78cdb7s"/></g></mask></defs><path mask="url(#SVGcRltieMe)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:road-sign-both" /></template>
