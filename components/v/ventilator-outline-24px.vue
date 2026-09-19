<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hcwqt1boa.css';
import '../../css/q/qw94g-6ki.css';
import '../../css/m/mr5dngbcl.css';
import '../../css/h/hliflxb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hcwqt1boa"/><path class="qw94g-6ki"/><path clip-rule="evenodd" class="mr5dngbcl"/><path class="hliflxb2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ventilator-outline-24px" /></template>
