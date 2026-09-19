<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5-9u1vgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m5-9u1vgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:scale-balanced" /></template>
