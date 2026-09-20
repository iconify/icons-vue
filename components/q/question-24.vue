<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wom0x6b6m.css';
import '../../css/c/cw-owhbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wom0x6b6m"/><path clip-rule="evenodd" class="cw-owhbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:question-24" /></template>
