<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/p/ppp-0h--y.css';
import '../../css/s/sv6uwwbpt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb6ieSbiR"><g class="hv130ab-t"><path class="ppp-0h--y"/><path class="sv6uwwbpt"/></g></mask></defs><path mask="url(#SVGb6ieSbiR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shovel-one" /></template>
