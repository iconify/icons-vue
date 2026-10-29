<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vg7o3iwek.css';
import '../../css/g/gbz5sj1lw.css';
import '../../css/o/orbxgqi3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vg7o3iwek wm-k"/><path class="gbz5sj1lw wm-k"/><path class="orbxgqi3s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wrap-text-blueprint" /></template>
