<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pumb42b6l.css';
import '../../css/y/yl3hz14bt.css';
import '../../css/x/xmntywhuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pumb42b6l"/><circle class="yl3hz14bt"/><path class="xmntywhuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:photo-multiple" /></template>
