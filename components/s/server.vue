<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/eif_5fngc.css';
import '../../css/y/yw2fz4bys.css';
import '../../css/o/obupwye0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="eif_5fngc"/><path class="yw2fz4bys"/><path class="obupwye0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:server" /></template>
