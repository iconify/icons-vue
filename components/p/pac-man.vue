<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kah0nub8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kah0nub8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:pac-man" /></template>
