<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_qj26bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u_qj26bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tent-arrow-turn-left" /></template>
