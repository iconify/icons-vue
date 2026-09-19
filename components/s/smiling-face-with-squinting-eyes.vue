<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/b/bm-9awbcn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdziXTd4Z"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="bm-9awbcn"/></g></mask></defs><path mask="url(#SVGdziXTd4Z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:smiling-face-with-squinting-eyes" /></template>
