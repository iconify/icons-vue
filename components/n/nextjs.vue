<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms2y87bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ms2y87bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nextjs" /></template>
