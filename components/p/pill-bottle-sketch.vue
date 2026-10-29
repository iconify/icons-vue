<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cn9jjnbdz.css';
import '../../css/u/upw9jgwpi.css';
import '../../css/b/b80h1i44n.css';
import '../../css/z/z7llafbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cn9jjnbdz"/><path class="upw9jgwpi wm-a"/><path class="b80h1i44n wm-k"/><path class="wm-a z7llafbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pill-bottle-sketch" /></template>
