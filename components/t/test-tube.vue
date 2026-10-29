<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/o/oxujxybvl.css';
import '../../css/x/x91hgebnh.css';
import '../../css/x/xd60-huet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="oxujxybvl"/><path class="x91hgebnh"/><path class="xd60-huet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:test-tube" /></template>
