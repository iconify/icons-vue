<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wahs48v3a.css';
import '../../css/j/jtu742b3e.css';
import '../../css/f/f1z770bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wahs48v3a"/><path class="jtu742b3e"/><path class="f1z770bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:ui-step-indicator-2" /></template>
