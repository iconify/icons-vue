<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x_-1fk5qn.css';
import '../../css/u/u1r09_bgv.css';
import '../../css/l/loc2q-8hs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGXAla8c4b"><g class="v3_i3wktz"><path class="x_-1fk5qn"/><path class="u1r09_bgv"/><path class="loc2q-8hs"/></g></mask></defs><path mask="url(#SVGXAla8c4b)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sun" /></template>
