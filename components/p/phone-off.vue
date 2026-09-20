<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b78hd_rlk.css';
import '../../css/r/rn9fw-2lr.css';
import '../../css/y/yc2_9cb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b78hd_rlk"/><path class="rn9fw-2lr"/><path class="yc2_9cb1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:phone-off" /></template>
