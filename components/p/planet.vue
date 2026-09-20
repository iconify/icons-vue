<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvttj8bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kvttj8bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:planet" /></template>
