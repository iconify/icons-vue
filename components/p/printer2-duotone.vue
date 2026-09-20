<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m0lg4ccxu.css';
import '../../css/m/mxbtkwbjt.css';
import '../../css/g/gilv6ob-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m0lg4ccxu"/><path class="mxbtkwbjt"/><path class="gilv6ob-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:printer2-duotone" /></template>
