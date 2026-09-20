<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/psv_8pbss.css';
import '../../css/g/gqg3yod4m.css';
import '../../css/w/wm4obn4yw.css';
import '../../css/w/w-8v64vlj.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="psv_8pbss"/><path class="gqg3yod4m"/><path clip-rule="evenodd" class="wm4obn4yw"/><path class="w-8v64vlj"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:smartphone-home-button-circle" /></template>
