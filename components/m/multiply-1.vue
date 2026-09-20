<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr1r_p2bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nr1r_p2bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:multiply-1" /></template>
