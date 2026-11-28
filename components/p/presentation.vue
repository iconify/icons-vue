<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi5qcvhqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi5qcvhqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:presentation" /></template>
