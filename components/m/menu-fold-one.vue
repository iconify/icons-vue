<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fawnadrdb.css';
import '../../css/e/e4inwoy3s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGsYu5BdCs"><g class="v3_i3wktz"><path class="fawnadrdb"/><path class="e4inwoy3s"/></g></mask></defs><path mask="url(#SVGsYu5BdCs)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:menu-fold-one" /></template>
