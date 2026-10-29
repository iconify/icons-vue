<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pkgsfqbib.css';
import '../../css/y/y5rfibc6p.css';
import '../../css/j/jbi5v9bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pkgsfqbib wm-a"/><path class="wm-k y5rfibc6p"/><path class="jbi5v9bue wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rss-sketch" /></template>
