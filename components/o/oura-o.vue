<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd__n8i3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd__n8i3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:oura-o" /></template>
