<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8obj5_al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r8obj5_al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:polygonal-lasso-tool-flat" /></template>
