<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly7vjva2u.css';
import '../../css/s/siiy5zxln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ly7vjva2u"/><path class="siiy5zxln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:turtle-20" /></template>
