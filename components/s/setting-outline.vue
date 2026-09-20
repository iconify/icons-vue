<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/etcb43btd.css';
import '../../css/x/xe_mok4yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="etcb43btd"/><path class="xe_mok4yw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:setting-outline" /></template>
