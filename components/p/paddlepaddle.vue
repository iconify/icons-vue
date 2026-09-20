<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj0pjvbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj0pjvbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:paddlepaddle" /></template>
