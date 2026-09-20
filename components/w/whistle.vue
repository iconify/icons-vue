<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k61w4fflf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k61w4fflf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:whistle" /></template>
