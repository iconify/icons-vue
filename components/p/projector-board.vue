<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4a006b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="g4a006b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:projector-board" /></template>
