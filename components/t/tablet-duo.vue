<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g74ufgb1e.css';
import '../../css/h/hkcj5-bst.css';
import '../../css/z/z8x7oi4it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="g74ufgb1e"/><path class="hkcj5-bst wm-a"/><path class="z8x7oi4it"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tablet-duo" /></template>
