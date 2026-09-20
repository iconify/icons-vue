<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bb0jpsb4k.css';
import '../../css/x/x9i9hmbfe.css';
import '../../css/u/uj3brmbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bb0jpsb4k"/><path class="x9i9hmbfe"/><path clip-rule="evenodd" class="uj3brmbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-outline" /></template>
