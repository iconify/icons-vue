<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qhwzu4b0a.css';
import '../../css/t/tumqksvsx.css';
import '../../css/u/u_7ve-3cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qhwzu4b0a"/><path clip-rule="evenodd" class="tumqksvsx"/><path class="u_7ve-3cq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:send" /></template>
