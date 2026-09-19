<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1pl9mbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q1pl9mbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:train-front-fill" /></template>
