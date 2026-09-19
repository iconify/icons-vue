<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/n/nggy8zk9i.css';
import '../../css/v/vdxl1de5w.css';
import '../../css/c/ce5x70xbs.css';
import '../../css/p/phpum01kj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnVDfQbHj"><g class="ufeehvblu"><path class="nggy8zk9i"/><path clip-rule="evenodd" class="vdxl1de5w"/><path class="ce5x70xbs"/><path class="phpum01kj"/></g></mask></defs><path mask="url(#SVGnVDfQbHj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:poker" /></template>
