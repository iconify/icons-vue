<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3x_a9b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x_a9b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:the-finals" /></template>
