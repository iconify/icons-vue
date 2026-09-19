<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/i/ihjrgdqda.css';
import '../../css/b/bz7g4hjuc.css';
import '../../css/y/ykz1d-54r.css';
import '../../css/p/p-67x_y3b.css';
import '../../css/r/rd3vi7oyg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYUmmjbuK"><g class="hv130ab-t"><path class="ihjrgdqda"/><path class="bz7g4hjuc"/><path class="ykz1d-54r"/><path class="p-67x_y3b"/><path class="rd3vi7oyg"/></g></mask></defs><path mask="url(#SVGYUmmjbuK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:mascara" /></template>
