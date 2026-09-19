<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kznc4_ijf.css';
import '../../css/u/uxo98kmzz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxf3Vlb0g"><g class="v3_i3wktz"><path class="kznc4_ijf"/><path class="uxo98kmzz"/></g></mask></defs><path mask="url(#SVGxf3Vlb0g)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people-upload" /></template>
