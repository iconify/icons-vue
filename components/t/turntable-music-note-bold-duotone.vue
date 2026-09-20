<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pf1tdnshj.css';
import '../../css/o/onn26uc-u.css';
import '../../css/u/udh2xlitm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pf1tdnshj"/><path clip-rule="evenodd" class="onn26uc-u"/><path class="udh2xlitm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-music-note-bold-duotone" /></template>
