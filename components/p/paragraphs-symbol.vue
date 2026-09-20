<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w70lsgs8c.css';
import '../../css/d/dlpk8tb7x.css';
import '../../css/p/pvytqg7gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="w70lsgs8c"><path class="dlpk8tb7x"/><path class="pvytqg7gd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:paragraphs-symbol" /></template>
