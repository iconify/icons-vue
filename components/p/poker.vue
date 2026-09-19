<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dugufridm.css';
import '../../css/s/srynasjdu.css';
import '../../css/m/m6vioqbko.css';
import '../../css/s/sw1ouqb9w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGi9ljhdVb"><g class="v3_i3wktz"><path class="dugufridm"/><path clip-rule="evenodd" class="srynasjdu"/><path class="m6vioqbko"/><path class="sw1ouqb9w"/></g></mask></defs><path mask="url(#SVGi9ljhdVb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:poker" /></template>
