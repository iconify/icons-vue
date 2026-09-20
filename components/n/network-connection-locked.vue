<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mr7zqwbog.css';
import '../../css/u/usal8xb7u.css';
import '../../css/p/ph9bfgb1s.css';
import '../../css/v/vde5abbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mr7zqwbog"/><path class="usal8xb7u"/><path class="ph9bfgb1s"/><path class="vde5abbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:network-connection-locked" /></template>
