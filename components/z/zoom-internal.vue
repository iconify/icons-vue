<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fqzg-n1xw.css';
import '../../css/w/wekuv1b2d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0V93Schu"><g class="v3_i3wktz"><path class="fqzg-n1xw"/><path class="wekuv1b2d"/></g></mask></defs><path mask="url(#SVG0V93Schu)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:zoom-internal" /></template>
