<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jwbw5ab9c.css';
import '../../css/t/toc50hb6s.css';
import '../../css/x/x130rzb-a.css';
import '../../css/r/rqpj5qg5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jwbw5ab9c"/><path class="toc50hb6s"/><path class="x130rzb-a"/><path class="rqpj5qg5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:webcam-off-1" /></template>
