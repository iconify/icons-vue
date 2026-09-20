<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i6e72xb0h.css';
import '../../css/f/flce2614m.css';
import '../../css/c/c_zdt_bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i6e72xb0h"/><path class="flce2614m"/><path class="c_zdt_bqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-block-bold" /></template>
