<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j3wgoubmz.css';
import '../../css/o/oqzhvoi7w.css';
import '../../css/k/k_a-7jb4j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9a2Jtb1W"><g class="v3_i3wktz"><path class="j3wgoubmz"/><path class="oqzhvoi7w"/><path class="k_a-7jb4j"/></g></mask></defs><path mask="url(#SVG9a2Jtb1W)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mark" /></template>
