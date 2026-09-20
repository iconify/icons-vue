<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia1w134er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia1w134er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:matterdotjs" /></template>
