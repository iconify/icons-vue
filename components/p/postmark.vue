<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c0-ydxhpn.css';
import '../../css/i/ids849bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c0-ydxhpn"/><path class="ids849bmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:postmark" /></template>
