<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n1p3t8x8f.css';
import '../../css/d/d6f1zcb1z.css';
import '../../css/i/i3khix54k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="n1p3t8x8f"/><path class="d6f1zcb1z"/><path clip-rule="evenodd" class="i3khix54k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-minus-rounded-outline" /></template>
