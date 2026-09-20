<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvgij0b_x.css';
import '../../css/w/w0ntu2ieo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xvgij0b_x"/><path class="w0ntu2ieo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:menu-dots-circle-16" /></template>
