<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc9b90bna.css';
import '../../css/y/ysh5xgerc.css';
import '../../css/p/po0txjbom.css';
import '../../css/n/nl7257qqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="xc9b90bna"><path class="ysh5xgerc"/><ellipse class="po0txjbom"/><path class="nl7257qqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-list-bold" /></template>
