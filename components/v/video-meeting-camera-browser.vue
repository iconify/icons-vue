<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b75e_lodc.css';
import '../../css/b/bde9dkbcy.css';
import '../../css/o/o0e_e_brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b75e_lodc"/><path class="bde9dkbcy"/><path class="o0e_e_brz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-meeting-camera-browser" /></template>
