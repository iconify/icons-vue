<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sl82esoas.css';
import '../../css/c/cchyt3b-e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGV6DRCc9a"><g class="v3_i3wktz"><path class="sl82esoas"/><path class="cchyt3b-e"/></g></mask></defs><path mask="url(#SVGV6DRCc9a)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:volume-small" /></template>
