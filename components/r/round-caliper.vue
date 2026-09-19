<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/geju8gabu.css';
import '../../css/g/gkm71ts8s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEcdaPLBx"><g class="aql7dnt-u"><path class="geju8gabu"/><path class="gkm71ts8s"/></g></mask></defs><path mask="url(#SVGEcdaPLBx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:round-caliper" /></template>
