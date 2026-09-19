<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bieyuq2ue.css';
import '../../css/d/d9or84w3r.css';
import '../../css/f/frytnybvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="bieyuq2ue"/><path clip-rule="evenodd" class="d9or84w3r"/><path class="frytnybvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vomitting" /></template>
