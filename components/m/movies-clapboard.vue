<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xh5-s8jmy.css';
import '../../css/e/er1u1bb_c.css';
import '../../css/e/e-hg7fm7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xh5-s8jmy"/><path class="er1u1bb_c"/><path class="e-hg7fm7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:movies-clapboard" /></template>
