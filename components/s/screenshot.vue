<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qrqa4j2-g.css';
import '../../css/m/mdfd69mwt.css';
import '../../css/e/eb3peub-j.css';
import '../../css/m/m-2iqioyf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGf5iufcGu"><g class="v3_i3wktz"><path class="qrqa4j2-g"/><path class="mdfd69mwt"/><path class="eb3peub-j"/><path class="m-2iqioyf"/></g></mask></defs><path mask="url(#SVGf5iufcGu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:screenshot" /></template>
