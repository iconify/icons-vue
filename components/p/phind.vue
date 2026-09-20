<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1sgfy4bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1sgfy4bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:phind" /></template>
