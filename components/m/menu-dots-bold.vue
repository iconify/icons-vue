<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dnk3glbbr.css';
import '../../css/x/xii-u1kii.css';
import '../../css/r/r9jbezb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dnk3glbbr"/><path class="xii-u1kii"/><path class="r9jbezb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-bold" /></template>
