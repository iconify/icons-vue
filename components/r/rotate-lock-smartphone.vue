<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qlodfi8rw.css';
import '../../css/x/x35k9g5le.css';
import '../../css/t/t044i1_sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qlodfi8rw"/><path class="x35k9g5le"/><path class="t044i1_sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:rotate-lock-smartphone" /></template>
