<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dt8jlkbav.css';
import '../../css/a/afpz-89xh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4Xv1gcFj"><g class="v3_i3wktz"><path class="dt8jlkbav"/><path class="afpz-89xh"/></g></mask></defs><path mask="url(#SVG4Xv1gcFj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:thumbs-up" /></template>
