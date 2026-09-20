<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_g3mrghf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_g3mrghf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:replay-30-line" /></template>
