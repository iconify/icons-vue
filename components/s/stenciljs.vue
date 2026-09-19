<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1pik2bez.css';
import '../../css/s/sm4_besjl.css';
import '../../css/d/d_zjw_mcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="z1pik2bez"/><path class="sm4_besjl"/><path class="d_zjw_mcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:stenciljs" /></template>
