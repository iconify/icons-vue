<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5_ix3xhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u5_ix3xhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:unreal-engine" /></template>
