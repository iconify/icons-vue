<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dgz6obkql.css';
import '../../css/d/dj7q2sbav.css';
import '../../css/p/pme4-2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dgz6obkql"/><path clip-rule="evenodd" class="dj7q2sbav"/><path clip-rule="evenodd" class="pme4-2byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mental-disorders2x-outline" /></template>
