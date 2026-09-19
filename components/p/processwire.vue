<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7wt5d-rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n7wt5d-rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:processwire" /></template>
