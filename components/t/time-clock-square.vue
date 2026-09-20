<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/p4d9vmb1h.css';
import '../../css/c/ckvwzsyka.css';
import '../../css/i/i3a2c48-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="p4d9vmb1h"/><path class="ckvwzsyka"/><path class="i3a2c48-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:time-clock-square" /></template>
