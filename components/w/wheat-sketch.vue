<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z6ruasb5p.css';
import '../../css/b/b-gg86l-v.css';
import '../../css/n/n1d3l-bkk.css';
import '../../css/t/t93sacb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z6ruasb5p"/><path class="b-gg86l-v wm-a"/><path class="n1d3l-bkk wm-k"/><path class="t93sacb0x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wheat-sketch" /></template>
