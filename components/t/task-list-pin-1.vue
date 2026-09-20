<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t-wkp8hgq.css';
import '../../css/g/grfl72bbk.css';
import '../../css/r/rj-6c4bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="t-wkp8hgq"/><path class="grfl72bbk"/><path class="rj-6c4bkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:task-list-pin-1" /></template>
