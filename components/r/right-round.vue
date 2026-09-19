<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeyjrzb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jeyjrzb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:right-round" /></template>
