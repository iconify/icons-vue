<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o5wplb8az.css';
import '../../css/v/vh953qb-o.css';
import '../../css/v/vu5m30bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o5wplb8az"/><path clip-rule="evenodd" class="vh953qb-o"/><path class="vu5m30bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mask-sad" /></template>
