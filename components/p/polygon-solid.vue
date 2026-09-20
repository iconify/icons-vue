<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcpoq0b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lcpoq0b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:polygon-solid" /></template>
