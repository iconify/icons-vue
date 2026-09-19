<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq0qa4bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dq0qa4bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pin-angle" /></template>
