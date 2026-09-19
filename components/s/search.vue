<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fh8rzobwg.css';
import '../../css/x/xfulg0g6i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzmt0MemV"><g class="v3_i3wktz"><path class="fh8rzobwg"/><path class="xfulg0g6i"/></g></mask></defs><path mask="url(#SVGzmt0MemV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:search" /></template>
