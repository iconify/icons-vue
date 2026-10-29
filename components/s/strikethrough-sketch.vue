<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/za-y1svgo.css';
import '../../css/k/khw2__bqg.css';
import '../../css/l/lo43kub9k.css';
import '../../css/b/bstijcuuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k za-y1svgo"/><path class="khw2__bqg wm-a"/><path class="lo43kub9k wm-k"/><path class="bstijcuuk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:strikethrough-sketch" /></template>
