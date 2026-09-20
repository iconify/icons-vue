<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b60eo5bxw.css';
import '../../css/i/i_hca-bhh.css';
import '../../css/f/fno7as3wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b60eo5bxw"/><path class="i_hca-bhh"/><path clip-rule="evenodd" class="fno7as3wa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-rotate-bold" /></template>
