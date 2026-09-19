<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a6skkmbbi.css';
import '../../css/e/esnmy5zcs.css';
import '../../css/b/bosa9ybls.css';
import '../../css/v/v3s_eybff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="a6skkmbbi"/><path class="esnmy5zcs"/><path class="bosa9ybls"/><path class="v3s_eybff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:voice-message" /></template>
