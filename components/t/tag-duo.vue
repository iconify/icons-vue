<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c4zeuubly.css';
import '../../css/e/e61c4pwgm.css';
import '../../css/d/dyl9j_8su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="c4zeuubly"/><path class="e61c4pwgm wm-a"/><path class="dyl9j_8su"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tag-duo" /></template>
