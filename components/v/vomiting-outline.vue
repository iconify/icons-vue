<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3nuceysm.css';
import '../../css/n/na_e5mbnk.css';
import '../../css/p/poz5v4vlw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r3nuceysm"/><path class="na_e5mbnk"/><path clip-rule="evenodd" class="poz5v4vlw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vomiting-outline" /></template>
