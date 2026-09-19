<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo-h30yov.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAj84feQA"><path class="xo-h30yov"/></mask></defs><path mask="url(#SVGAj84feQA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sort" /></template>
