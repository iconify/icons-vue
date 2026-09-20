<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/ootwnmxuy.css';
import '../../css/e/eyn1tubqg.css';
import '../../css/g/g68tbfbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ootwnmxuy"/><path class="eyn1tubqg"/><path class="g68tbfbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mailbox-bold" /></template>
