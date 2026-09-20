<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fey1rubmg.css';
import '../../css/k/kgcxlh52x.css';
import '../../css/m/mo3nibcdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fey1rubmg"/><path class="kgcxlh52x"/><path class="mo3nibcdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-game-360-vr" /></template>
