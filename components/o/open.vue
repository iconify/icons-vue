<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b-33s3b6f.css';
import '../../css/o/ohkx9_wlw.css';
import '../../css/s/s_l2cxbxm.css';
import '../../css/r/rwp25fbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="b-33s3b6f"/><path class="ohkx9_wlw"/><path class="s_l2cxbxm"/><path class="rwp25fbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:open" /></template>
