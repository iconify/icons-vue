<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruf9kkree.css';
import '../../css/n/n0nc54wee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ruf9kkree"/><path class="n0nc54wee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:power" /></template>
