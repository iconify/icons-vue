<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sk-2_lbxb.css';
import '../../css/c/cp13a2bsj.css';
import '../../css/f/f72ylivjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sk-2_lbxb"/><path class="cp13a2bsj"/><path class="f72ylivjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scroll-text-duotone" /></template>
