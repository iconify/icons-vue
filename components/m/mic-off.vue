<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js103e65u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":512};
const content = `<path class="js103e65u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mic-off" /></template>
