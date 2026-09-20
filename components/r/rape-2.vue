<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe81y5u7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fe81y5u7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:rape-2" /></template>
