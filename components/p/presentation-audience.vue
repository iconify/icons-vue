<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qul6b_1xq.css';
import '../../css/k/kdanzpkky.css';
import '../../css/n/n60idm96g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qul6b_1xq"/><path class="kdanzpkky"/><path class="n60idm96g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:presentation-audience" /></template>
