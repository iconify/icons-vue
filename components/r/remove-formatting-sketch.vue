<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/ro8t4enop.css';
import '../../css/p/p4xp11bjk.css';
import '../../css/y/y8ndjjvgg.css';
import '../../css/r/rpa3wcr1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ro8t4enop wm-k"/><path class="p4xp11bjk wm-s"/><path class="wm-k y8ndjjvgg"/><path class="rpa3wcr1x wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:remove-formatting-sketch" /></template>
