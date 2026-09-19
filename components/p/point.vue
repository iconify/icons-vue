<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4369xzyz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdfUibcAN"><path class="u4369xzyz"/></mask></defs><path mask="url(#SVGdfUibcAN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:point" /></template>
