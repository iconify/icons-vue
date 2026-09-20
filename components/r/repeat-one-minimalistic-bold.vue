<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iz7pr1buf.css';
import '../../css/e/evitbbbdh.css';
import '../../css/o/onsp0_bsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iz7pr1buf"/><path clip-rule="evenodd" class="evitbbbdh"/><path class="onsp0_bsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-minimalistic-bold" /></template>
