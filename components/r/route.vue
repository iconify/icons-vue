<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vo8jwqa7q.css';
import '../../css/n/nn1ewrbff.css';
import '../../css/y/yaeyb-g4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><circle class="vo8jwqa7q"/><path class="nn1ewrbff"/><circle class="yaeyb-g4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:route" /></template>
