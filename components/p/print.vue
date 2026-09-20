<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/e/ek8eycbfz.css';
import '../../css/b/b4q5icciq.css';
import '../../css/z/zbx2d_b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="ek8eycbfz"/><path class="b4q5icciq"/><path class="zbx2d_b7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:print" /></template>
