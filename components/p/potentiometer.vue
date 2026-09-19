<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/w/wnnt2d18d.css';
import '../../css/f/flzcbdc4z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVD5AleDS"><g class="aql7dnt-u"><ellipse class="wnnt2d18d"/><path class="flzcbdc4z"/></g></mask></defs><path mask="url(#SVGVD5AleDS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:potentiometer" /></template>
