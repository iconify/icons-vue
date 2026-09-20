<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3z-_y6_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t3z-_y6_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:virtual-reality-solid" /></template>
