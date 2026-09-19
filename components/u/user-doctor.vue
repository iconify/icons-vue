<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsnjhj1vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tsnjhj1vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-doctor" /></template>
