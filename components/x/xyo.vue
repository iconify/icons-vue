<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll-v7cc5a.css';
import '../../css/t/t7ok3w4ym.css';
import '../../css/o/onfmwrbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll-v7cc5a"/><path class="t7ok3w4ym"/><path class="onfmwrbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xyo" /></template>
