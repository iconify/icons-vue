<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hmajdsbvs.css';
import '../../css/x/x70s9bt2g.css';
import '../../css/n/n2j85qahi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hmajdsbvs"/><path class="x70s9bt2g"/><path class="n2j85qahi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-game-controller-wifi" /></template>
