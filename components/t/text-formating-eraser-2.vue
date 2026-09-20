<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/ne9whfbid.css';
import '../../css/f/fnzkjf6tn.css';
import '../../css/t/tv4babcjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ne9whfbid"/><path class="fnzkjf6tn"/><path class="tv4babcjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:text-formating-eraser-2" /></template>
