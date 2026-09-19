<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f89y2qbtf.css';
import '../../css/u/u1ez71txv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f89y2qbtf"/><path class="u1ez71txv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-color-stroke-12" /></template>
