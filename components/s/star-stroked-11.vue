<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7p-x_2jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="k7p-x_2jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:star-stroked-11" /></template>
