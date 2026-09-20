<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/eayipj5ml.css';
import '../../css/s/sgz67zbcf.css';
import '../../css/c/czb17zbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="eayipj5ml"/><path class="sgz67zbcf"/><circle class="czb17zbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pin-alt-light" /></template>
