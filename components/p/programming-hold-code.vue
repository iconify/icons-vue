<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o1y6l8rmk.css';
import '../../css/r/r1iymrb_r.css';
import '../../css/d/dwxujfbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o1y6l8rmk"/><path class="r1iymrb_r"/><path class="dwxujfbtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:programming-hold-code" /></template>
