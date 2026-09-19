<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrp22s0pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrp22s0pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sliders-h" /></template>
