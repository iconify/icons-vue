<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pmwvltbwu.css';
import '../../css/b/bso_8zbol.css';
import '../../css/c/cbkt77dxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pmwvltbwu"/><path class="bso_8zbol"/><path class="cbkt77dxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rolling-pin-bold" /></template>
