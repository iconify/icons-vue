<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jp6i8srxc.css';
import '../../css/u/u966ymbyk.css';
import '../../css/a/am7se9eaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="jp6i8srxc"/><path clip-rule="evenodd" class="u966ymbyk"/><path clip-rule="evenodd" class="am7se9eaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:ticket" /></template>
