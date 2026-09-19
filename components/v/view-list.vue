<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gztd8-bpl.css';
import '../../css/d/d9o7i0q2s.css';
import '../../css/f/fl45o4a_e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGByU5edwj"><g class="ft5dv1b6b"><rect class="gztd8-bpl"/><path class="d9o7i0q2s"/><path clip-rule="evenodd" class="fl45o4a_e"/></g></mask></defs><path mask="url(#SVGByU5edwj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:view-list" /></template>
