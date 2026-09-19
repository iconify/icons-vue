<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsypm3bfl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqWfAeCxt"><path class="qsypm3bfl"/></mask></defs><path mask="url(#SVGqWfAeCxt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:panorama-horizontal" /></template>
