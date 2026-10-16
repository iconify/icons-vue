<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pufzx1blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440.71,"height":440.63,"left":36.13,"top":36.34};
const content = `<path class="pufzx1blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ryot-light" /></template>
