<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/awuprrb2l.css';
import '../../css/s/sigei6ulc.css';
import '../../css/h/hh3b10bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="awuprrb2l"/><path class="sigei6ulc"/><path class="hh3b10bzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-x-duotone" /></template>
