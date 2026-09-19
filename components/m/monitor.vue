<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bv4586n5c.css';
import '../../css/s/sqpivhksc.css';
import '../../css/k/kivyvktmd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn7lS4UgA"><g class="v3_i3wktz"><path class="bv4586n5c"/><path clip-rule="evenodd" class="sqpivhksc"/><path class="kivyvktmd"/></g></mask></defs><path mask="url(#SVGn7lS4UgA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:monitor" /></template>
