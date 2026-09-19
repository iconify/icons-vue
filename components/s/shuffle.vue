<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv95d0kjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qv95d0kjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shuffle" /></template>
