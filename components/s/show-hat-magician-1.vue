<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/z99vifmop.css';
import '../../css/m/mrwtbc_ba.css';
import '../../css/v/v76fh54tr.css';
import '../../css/b/bxqz_zugs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="z99vifmop"/><path class="mrwtbc_ba"/><path class="v76fh54tr"/><path class="bxqz_zugs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:show-hat-magician-1" /></template>
