<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dnk3glbbr.css';
import '../../css/r/r9jbezb2f.css';
import '../../css/q/q3xuzddzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dnk3glbbr"/><path class="r9jbezb2f"/><path class="q3xuzddzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-bold-duotone" /></template>
