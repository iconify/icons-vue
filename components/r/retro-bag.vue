<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/m/midqvbcgl.css';
import '../../css/c/c0gmrobzl.css';
import '../../css/r/r47dkf1hc.css';
import '../../css/z/zd46sgbja.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpWVYQcrI"><g class="aql7dnt-u"><path class="midqvbcgl"/><path class="c0gmrobzl"/><path class="r47dkf1hc"/><path class="zd46sgbja"/></g></mask></defs><path mask="url(#SVGpWVYQcrI)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:retro-bag" /></template>
