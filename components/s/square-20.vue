<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c961mpvnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c961mpvnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-20" /></template>
