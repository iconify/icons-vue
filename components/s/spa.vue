<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f41sj1dgi.css';
import '../../css/o/o9f842q3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f41sj1dgi"/><path class="o9f842q3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:spa" /></template>
