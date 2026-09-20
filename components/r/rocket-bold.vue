<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eub-owb9l.css';
import '../../css/b/bnr386b3y.css';
import '../../css/o/omtfbmb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eub-owb9l"/><path class="bnr386b3y"/><path clip-rule="evenodd" class="omtfbmb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-bold" /></template>
