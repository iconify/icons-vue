<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj7n45bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="aj7n45bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:skull-crossbones" /></template>
