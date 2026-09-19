<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l9loqrvgk.css';
import '../../css/t/tmh83rwbo.css';
import '../../css/p/p97oy8mpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":38,"height":32};
const content = `<g class="cuyn6tgcc"><path class="l9loqrvgk"/><path class="tmh83rwbo"/><circle class="p97oy8mpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:wallet" /></template>
