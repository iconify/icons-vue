<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/t/tvgauyb5v.css';
import '../../css/b/b77-k2blg.css';
import '../../css/q/qczrjccey.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzfmErcyW"><g class="s9cl3zbei"><path class="tvgauyb5v"/><path class="b77-k2blg"/><path class="qczrjccey"/></g></mask></defs><path mask="url(#SVGzfmErcyW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:movie" /></template>
