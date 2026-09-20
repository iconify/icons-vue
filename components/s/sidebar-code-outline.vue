<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vc6nhhbik.css';
import '../../css/i/i0n9u8biz.css';
import '../../css/x/x3bg3uy2c.css';
import '../../css/a/a9mvgcnyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vc6nhhbik"/><path class="i0n9u8biz"/><path class="x3bg3uy2c"/><path clip-rule="evenodd" class="a9mvgcnyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-code-outline" /></template>
