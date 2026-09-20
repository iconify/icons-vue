<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xy5tg3qjq.css';
import '../../css/f/f1wgwye4w.css';
import '../../css/t/t4lvtfbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xy5tg3qjq"/><path class="f1wgwye4w"/><path clip-rule="evenodd" class="t4lvtfbbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget-add" /></template>
