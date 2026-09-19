<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tvl0obccn.css';
import '../../css/x/xiuiabbcc.css';
import '../../css/o/ofo04lg3k.css';
import '../../css/x/xkpy2fb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tvl0obccn"/><path class="xiuiabbcc"/><path clip-rule="evenodd" class="ofo04lg3k"/><path class="xkpy2fb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:train" /></template>
