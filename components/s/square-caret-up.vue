<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc3tac-mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fc3tac-mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-caret-up" /></template>
