<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qmgrdexng.css';
import '../../css/r/r4dlvobwc.css';
import '../../css/x/x7pgg2f2r.css';
import '../../css/o/o1fxrtmvk.css';
import '../../css/e/ekf-2nkms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qmgrdexng wm-deco"/><path class="r4dlvobwc wm-deco"/><path class="wm-deco x7pgg2f2r"/><path class="o1fxrtmvk wm-k"/><path class="ekf-2nkms wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sigma-blueprint" /></template>
