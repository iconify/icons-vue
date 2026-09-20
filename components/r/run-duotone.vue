<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/orenz6bgo.css';
import '../../css/y/yu4vhebzc.css';
import '../../css/e/etnnbijno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="orenz6bgo"/><path clip-rule="evenodd" class="yu4vhebzc"/><path class="etnnbijno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:run-duotone" /></template>
