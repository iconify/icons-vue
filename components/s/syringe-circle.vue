<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/c/cmnjqccwy.css';
import '../../css/a/akxs6rb3u.css';
import '../../css/e/e39n-3-ig.css';
import '../../css/k/kfo6mbbne.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path clip-rule="evenodd" class="cmnjqccwy"/><path clip-rule="evenodd" class="akxs6rb3u"/><path class="e39n-3-ig"/><path class="kfo6mbbne"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:syringe-circle" /></template>
