<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bnof37xfk.css';
import '../../css/h/hmx43h1zy.css';
import '../../css/q/qh2e39yog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bnof37xfk"/><path class="hmx43h1zy"/><path class="qh2e39yog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:paragraphs-indent" /></template>
