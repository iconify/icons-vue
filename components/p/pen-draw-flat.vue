<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkl4wyb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkl4wyb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:pen-draw-flat" /></template>
