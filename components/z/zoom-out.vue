<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9koci0im.css';
import '../../css/h/hoxqff5ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9koci0im"/><path class="hoxqff5ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:zoom-out" /></template>
