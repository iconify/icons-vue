<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du109jbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="du109jbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:sky-panorama" /></template>
