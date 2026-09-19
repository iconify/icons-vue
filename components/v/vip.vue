<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/n7f99bojn.css';
import '../../css/p/ptxldtbxo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfIgoeeRz"><g class="v3_i3wktz"><path class="n7f99bojn"/><path class="ptxldtbxo"/></g></mask></defs><path mask="url(#SVGfIgoeeRz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:vip" /></template>
