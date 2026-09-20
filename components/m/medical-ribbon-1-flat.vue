<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrq-fmbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mrq-fmbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:medical-ribbon-1-flat" /></template>
