<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3j_46yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3j_46yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:microstation" /></template>
