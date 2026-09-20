<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/ye3wqyb1x.css';
import '../../css/s/sm7_bzb8m.css';
import '../../css/n/nqfsodb3k.css';
import '../../css/a/az22wsfsd.css';
import '../../css/k/kfn5c6bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ye3wqyb1x"/><path class="sm7_bzb8m"/><path class="nqfsodb3k"/><path class="az22wsfsd"/><path class="kfn5c6bim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:strategy-target-center-phone" /></template>
