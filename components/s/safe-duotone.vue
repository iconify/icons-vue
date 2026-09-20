<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e5uzaw6kb.css';
import '../../css/x/xpzro9uft.css';
import '../../css/g/gomzfyb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e5uzaw6kb"/><path clip-rule="evenodd" class="xpzro9uft"/><path clip-rule="evenodd" class="gomzfyb9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:safe-duotone" /></template>
