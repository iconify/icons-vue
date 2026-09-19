<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/afw5bxb9f.css';
import '../../css/s/s51uqybkz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu13uHDQK"><g class="v3_i3wktz"><path class="afw5bxb9f"/><path class="s51uqybkz"/></g></mask></defs><path mask="url(#SVGu13uHDQK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:play-wrong" /></template>
