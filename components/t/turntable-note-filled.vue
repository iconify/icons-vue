<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fsvgi0bxr.css';
import '../../css/e/eojx8bb3q.css';
import '../../css/z/zxkqjubrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fsvgi0bxr"/><path class="eojx8bb3q"/><path clip-rule="evenodd" class="zxkqjubrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:turntable-note-filled" /></template>
