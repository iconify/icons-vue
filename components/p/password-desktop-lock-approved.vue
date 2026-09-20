<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xl07tt-6b.css';
import '../../css/f/fmam1lxxs.css';
import '../../css/c/ct1flbcol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xl07tt-6b"/><path class="fmam1lxxs"/><path class="ct1flbcol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:password-desktop-lock-approved" /></template>
