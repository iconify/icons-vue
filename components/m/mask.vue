<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/azokiuq7x.css';
import '../../css/q/q3jhrhbxa.css';
import '../../css/c/ctmd9xbxy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOjViQcyF"><g class="s9cl3zbei"><path clip-rule="evenodd" class="azokiuq7x"/><path class="q3jhrhbxa"/><path class="ctmd9xbxy"/></g></mask></defs><path mask="url(#SVGOjViQcyF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mask" /></template>
