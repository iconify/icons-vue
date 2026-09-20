<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9skjwb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i9skjwb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:vending-machine" /></template>
