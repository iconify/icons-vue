<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/phk9uibbc.css';
import '../../css/c/c5dd8mb9u.css';
import '../../css/h/h7sstobfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="phk9uibbc"/><path class="c5dd8mb9u"/><path class="h7sstobfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:seat-vip" /></template>
