<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xo2h4kz3i.css';
import '../../css/a/adtlylf5k.css';
import '../../css/x/x489igpny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xo2h4kz3i"/><path clip-rule="evenodd" class="adtlylf5k"/><path class="x489igpny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:smartphone2-print" /></template>
