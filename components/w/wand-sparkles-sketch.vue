<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j-h8fsb7z.css';
import '../../css/i/ixiy87sdk.css';
import '../../css/x/xdyx-3bcl.css';
import '../../css/e/ercz5snjv.css';
import '../../css/p/p05bdcbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j-h8fsb7z"/><path class="ixiy87sdk wm-k"/><path class="wm-a xdyx-3bcl"/><path class="ercz5snjv wm-k"/><path class="p05bdcbap wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wand-sparkles-sketch" /></template>
