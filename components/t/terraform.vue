<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/z/zv06l1bpv.css';
import '../../css/h/hcafqxmbj.css';
import '../../css/k/kdt1gpbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="d2kvgvbvc"><path class="zv06l1bpv"/><path class="hcafqxmbj"/><path class="kdt1gpbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:terraform" /></template>
