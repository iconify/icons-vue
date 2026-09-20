<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4x_l744s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4x_l744s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zingat" /></template>
