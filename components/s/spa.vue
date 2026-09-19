<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbj5fzbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbj5fzbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:spa" /></template>
