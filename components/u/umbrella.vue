<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/k4z5r1wzq.css';
import '../../css/s/smf_smbgh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTG4Gvere"><g class="v3_i3wktz"><path class="k4z5r1wzq"/><path class="smf_smbgh"/></g></mask></defs><path mask="url(#SVGTG4Gvere)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:umbrella" /></template>
