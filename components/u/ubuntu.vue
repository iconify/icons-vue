<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/uo05yyjpj.css';
import '../../css/f/fm01msbde.css';
import '../../css/g/g1o6erbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="uo05yyjpj"/><path class="fm01msbde"/><path class="g1o6erbxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:ubuntu" /></template>
