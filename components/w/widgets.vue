<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4cg4-ctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":416};
const content = `<path class="h4cg4-ctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:widgets" /></template>
