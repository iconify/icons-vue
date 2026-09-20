<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p6jvy1bcp.css';
import '../../css/a/a12-1fbxe.css';
import '../../css/c/c6sd4lv5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p6jvy1bcp"/><path class="a12-1fbxe"/><path class="c6sd4lv5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-2-bold" /></template>
