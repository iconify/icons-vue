<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t9olzz3pl.css';
import '../../css/i/ijeaupbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="t9olzz3pl"/><path class="ijeaupbvl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:paypal" /></template>
