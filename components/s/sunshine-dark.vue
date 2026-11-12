<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grfi6tbpu.css';
import '../../css/r/rwxu_6bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="grfi6tbpu"/><path class="rwxu_6bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sunshine-dark" /></template>
