<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lzf9x5vrh.css';
import '../../css/z/z9wq9ylvw.css';
import '../../css/x/x2m96xbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lzf9x5vrh"/><path class="z9wq9ylvw"/><path clip-rule="evenodd" class="x2m96xbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:memo-plus" /></template>
