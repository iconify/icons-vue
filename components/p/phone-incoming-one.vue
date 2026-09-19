<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/runx2ohsi.css';
import '../../css/e/e-xtayzvh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMzFSTbVG"><g class="v3_i3wktz"><path class="runx2ohsi"/><path class="e-xtayzvh"/></g></mask></defs><path mask="url(#SVGMzFSTbVG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:phone-incoming-one" /></template>
