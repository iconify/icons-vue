<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fyv63n06x.css';
import '../../css/g/ge2z8-slh.css';
import '../../css/l/l8-q0ccsa.css';
import '../../css/k/k-3466b-a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdIn5hdef"><g class="aql7dnt-u"><path class="fyv63n06x"/><path class="ge2z8-slh"/><path class="l8-q0ccsa"/><path class="k-3466b-a"/></g></mask></defs><path mask="url(#SVGdIn5hdef)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:map-road-two" /></template>
