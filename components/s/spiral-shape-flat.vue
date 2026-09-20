<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkxrs8bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kkxrs8bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:spiral-shape-flat" /></template>
