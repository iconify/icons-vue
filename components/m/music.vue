<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xa2d9bb0k.css';
import '../../css/j/jroqwgjpq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLiEztcGW"><g class="v3_i3wktz"><path class="xa2d9bb0k"/><path class="jroqwgjpq"/></g></mask></defs><path mask="url(#SVGLiEztcGW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:music" /></template>
