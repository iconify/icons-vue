<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/naayrx7_t.css';
import '../../css/n/nnyeuib9r.css';
import '../../css/s/s0zjehfxn.css';
import '../../css/a/a0myg2b6y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRFv1Npxo"><g class="v3_i3wktz"><path class="naayrx7_t"/><path clip-rule="evenodd" class="nnyeuib9r"/><path class="s0zjehfxn"/><path class="a0myg2b6y"/></g></mask></defs><path mask="url(#SVGRFv1Npxo)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:tape" /></template>
