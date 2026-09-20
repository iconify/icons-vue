<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c66c8d1xn.css';
import '../../css/e/esrfit-bu.css';
import '../../css/e/ege2gyb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c66c8d1xn"/><path class="esrfit-bu"/><path class="ege2gyb9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:microphone-karaoke-1" /></template>
