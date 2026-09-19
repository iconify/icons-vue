<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5n1f5bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="g5n1f5bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mars" /></template>
