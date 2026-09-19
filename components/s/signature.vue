<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh4scibww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="eh4scibww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:signature" /></template>
