<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyddhdbvg.css';
import '../../css/y/yr5bhhobf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wyddhdbvg"/><path class="yr5bhhobf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:play-circle" /></template>
