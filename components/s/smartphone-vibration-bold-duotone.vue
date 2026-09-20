<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s7y57bcmv.css';
import '../../css/l/lkz8h1lgg.css';
import '../../css/y/y0brb2b7c.css';
import '../../css/n/nous9knry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s7y57bcmv"/><path class="lkz8h1lgg"/><path class="y0brb2b7c"/><path class="nous9knry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-vibration-bold-duotone" /></template>
