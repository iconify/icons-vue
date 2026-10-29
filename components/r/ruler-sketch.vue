<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/on45fbcsd.css';
import '../../css/j/jwcc8uoss.css';
import '../../css/r/rstq11b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="on45fbcsd"/><path class="jwcc8uoss wm-k"/><path class="rstq11b5k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ruler-sketch" /></template>
