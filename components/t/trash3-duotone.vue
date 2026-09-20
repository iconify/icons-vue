<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d_chcnbrk.css';
import '../../css/s/su39-7f4f.css';
import '../../css/a/at1ai5bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d_chcnbrk"/><path class="su39-7f4f"/><path clip-rule="evenodd" class="at1ai5bbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash3-duotone" /></template>
