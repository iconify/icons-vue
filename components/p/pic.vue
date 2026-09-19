<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x9u4gylcp.css';
import '../../css/i/ixqdcsbvp.css';
import '../../css/x/x6bijybfe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGh2FVndaf"><g class="v3_i3wktz"><path clip-rule="evenodd" class="x9u4gylcp"/><path clip-rule="evenodd" class="ixqdcsbvp"/><path class="x6bijybfe"/></g></mask></defs><path mask="url(#SVGh2FVndaf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pic" /></template>
