<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/d/dudy4jk-t.css';
import '../../css/x/xln2qqbsu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGur1HAdmZ"><g class="v3_i3wktz"><path class="vkcj4bcdm"/><path class="dudy4jk-t"/><path class="xln2qqbsu"/></g></mask></defs><path mask="url(#SVGur1HAdmZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:multi-circular" /></template>
