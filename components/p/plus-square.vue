<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz1kzcj3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mz1kzcj3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:plus-square" /></template>
