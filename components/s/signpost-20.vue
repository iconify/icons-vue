<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uma6ucy9m.css';
import '../../css/f/f-a0_gbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uma6ucy9m"/><path class="f-a0_gbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signpost-20" /></template>
