<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfi69eb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="hfi69eb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:running" /></template>
