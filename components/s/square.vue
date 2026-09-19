<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd27rseip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="gd27rseip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:square" /></template>
