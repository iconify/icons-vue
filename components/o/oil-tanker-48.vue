<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dssydwbjm.css';
import '../../css/u/uzp27665y.css';
import '../../css/z/zp5y05ahx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dssydwbjm"/><path class="uzp27665y"/><path class="zp5y05ahx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oil-tanker-48" /></template>
