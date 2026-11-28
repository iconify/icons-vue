<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7-9-q0ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7-9-q0ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:soccer-ball-check" /></template>
